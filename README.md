# DISCLAIMER
This project and all contained code is provided as-is with no guarantee or warranty concerning the usability or impact on systems. This content may be used, distributed, and modified, provided all parties involved agree that Microsoft and Microsoft Partners are not responsible for the produced outcome. Microsoft will not provide any support through any means.

## Importing the Configuration Baseline
1. Download the latest version of the baseline.
2. Open the **Configuration Manager** console.
3. From the **Assets and Compliance** workspace, expand **Compliance Settings**.
4. Right-click on **Configuration Baselines** and select **Import Configuration Data**.
5. On the **Import Configuration Data** Wizard, click **Add** and select the baseline. 
6. Click **Yes** on the publisher notification.
7. With the baseline selected, click **Next**.
8. On the **Summary** page, review the Configuration Baseline and Configuration Items that will be imported. Click **Next** to complete the import.
9. On the Confirmation page, click **Close**.

# Deploying the Configuration Baseline
1. From the **Assets and Compliance** workspace, expand **Compliance Settings** > **Configuration Baselines**.
2. Right-click on the new baseline and select **Deploy**.
3. On the deployment dialog window, select the appropriate values and click **OK**. 
    - Check the boxes for automatic remediation as appropriate for your environment. Consider deploying without remediation first to monitor impacted devices, then enable remediation after 1-2 days.
    - Select the device collection containing devices that require detection and remediation.
    - Set the deployment schedule appropriately for your environment.
