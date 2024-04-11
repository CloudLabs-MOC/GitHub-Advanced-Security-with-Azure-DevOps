# Lab 05: Microsoft Defender for Cloud DevOps security

## Lab Scenario

In this lab, we connect the Azure DevOps environment to Microsoft Defender for Cloud to enhance DevOps security. We will explore the DevOps security findings and inventory provided by Microsoft Defender for Cloud to review their security posture.

## Lab Objectives

In this lab, you will perform the following:

- Task 1: Connect Azure DevOps Environment to Microsoft Defender for Cloud
- Task 2: Understand your DevOps security

## Estimated Timing: 30 minutes

## Architecture Diagram

  ![AD](media/ard05.png)

### Task 1: Connect Azure DevOps Environment to Microsoft Defender for Cloud

1. Sign in to the Azure portal.

1. Go to **Microsoft Defender for Cloud** > **Environment settings**.

1. Select **Add Environment**.

1. Select **Azure DevOps**.

    ![alert_detected](media/advlab51.png)

1. On the **Azure DevOps Connection** page, under **Account details**, provide the below settings.

   | Setting  | Value |
   -----------|---------
   | Connector name | AzureDevopsconnector |
   | Resource group | LabVM |
   | Region | Select any supporting region |

    ![alert_detected](media/advlab52.png)

1. Select **Next: Configure access**

1. Select **Authorize**. Ensure you're authorizing the correct Azure Tenant using the drop-down menu in Azure DevOps and by verifying you're in the correct Azure Tenant in Defender for Cloud.

1. In the popup dialog, read the list of permission requests, and then select **Accept**.

    ![alert_detected](media/advlab53.png)

1. Leave all other settings as default.

1. Select **Next: Review and generate**.

1. Review the information, and then select **Create**.

1. Wait for some time to view the connector on the **Environment settings** page.

    ![alert_detected](media/advlab54.png)

### Task 2: Understanding your DevOps security

1. Navigate to **DevOps Security** under **Cloud Security**.

    ![alert_detected](media/advlab55.png)

1. The DevOps security findings and DevOps Inventory table are listed on the page, which helps to review the DevOps security posture.

    ![alert_detected](media/advlab56.png)

   >**Note:** It might take time to reflect the real-time status of **Advanced Security Status**.

## Review
In this lab, you have completed the following:

-  Connected Azure DevOps Environment to Microsoft Defender for Cloud.
-  Understood your DevOps security.

