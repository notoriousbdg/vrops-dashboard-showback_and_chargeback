
# Showback (Cost) and Chargeback (Price) Dashboards for vRealize Operations 8.2 and Cloud
---------

Use these [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboards and reports to showback the cost of VMs and vSphere Pods and to chargeback the price of VMs.

## Dashboards
### Dashboard: Showback (VM Cost)
![Dashboard: Showback (VM Cost)](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Dashboard-Showback_VM_Cost.png)

### Dashboard: Showback (vSphere Pod Cost)
![Dashboard: Showback (vSphere Pod Cost)](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Dashboard-Showback_vSphere_Pod_Cost.png)

### Dashboard: Chargeback (VM Price)
![Dashboard: Chargeback (VM Price)](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Dashboard-Chargeback_VM_Price.png)

### Dashboard: VM Cost vs. Price
![Dashboard: VM Cost vs. Price](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Dashobard-VM_Cost_vs_Price.png)

## Installation
1. Import the views at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/View_Import.png)
2. Click `Browse...` then select the file named [Views.zip](https://github.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/raw/main/Views.zip)
3. The included views are listed in the [Views section](#Views)
4. Import the dashboard at `Dashboards` / `Manage Dashboards` / `...` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Dashboard_Import.png)
5. Click `Browse...` then select the file named [Dashboards.zip](https://github.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/raw/main/Dashboards.zip)
6. The included dashboards are listed in the [Dashboards section](#Dashboard List)
7. Import the reports at `Dashboards` / `Reports` / `Import...`  
![Import Report](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/main/images/Report_Import.png)
8. Click `Browse...` then select the file named [Reports.zip](https://github.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/raw/main/Reports.zip)
9. The included reports are listed in the [Reports section](#Reports)

## Dashboard List
| Dashboard Name | Dashboard Path |
|--|--|
| Showback (VM Cost) | Shared Dashboards (GBrandon)/Cost |
| Showback (vSphere Pod Cost) | Shared Dashboards (GBrandon)/Cost |
| Chargeback (VM Price) | Shared Dashboards (GBrandon)/Price |
| VM Cost vs. Price | Shared Dashboards (GBrandon)/Price |

## Views
| View Name | Dashboard | Name on Dashboard | View Type |
|--|--|--|--|
| Cost &#124; VM Cost Summary | Showback (VM Cost) | Cost Summary (This Month) | Summary |
| Cost &#124; VM Cost Summary Pie | Showback (VM Cost) | VM Cost Distribution (Top 100) | Distribution |
| Cost &#124; VM Potential Savings | Showback (VM Cost) | Potential Savings (Top 20) | Distribution |
| Cost &#124; VM Cost Detail | Showback (VM Cost) | Members of the Group (Select to View Trend) | List |
| Cost &#124; VM Cost Trend | Showback (VM Cost) | Cost Trend of Selected VM | Trend |
| Cost &#124; vSphere Pod Cost Summary | Showback (vSphere Pod Cost) | Cost Summary (This Month) | Summary |
| Cost &#124; vSphere Pod Cost Summary Pie | Showback (vSphere Pod Cost) | vSphere Pod Cost Distribution (Top 100) | Distribution |
| Cost &#124; vSphere Pod Cost for Idle vSphere Pods | Showback (vSphere Pod Cost) | Idle vSphere Pods | List |
| Cost &#124; vSphere Pod Cost Detail | Showback (vSphere Pod Cost) | Members of the Group (Select to View Trend) | List |
| Cost &#124; vSphere Pod Cost Trend | Showback (VM Cost) | Cost Trend of Selected vSphere Pod | Trend |
| Price &#124; VM Price Summary | Chargeback (VM Price) | Price Summary of Selected Group | Summary |
| Price &#124; VM Price Summary Pie | Chargeback (VM Price) | VM Price Distribution (Top 100) | Distribution |
| Price &#124; VM Price for Powered Off VMs | Chargeback (VM Price) | Powered Off VMs | List |
| Price &#124; VM Price for Idle VMs | Chargeback (VM Price) | Idle VMs | List |
| Price &#124; VMs with Snapshots | Chargeback (VM Price) | VM with Snapshots | List |
| Price &#124; VM Price Detail | Chargeback (VM Price) | Price of VMs in Selected Object | List |
| VM Cost vs. Price &#124; VM Cost and Price Summary | VM Cost vs. Price | Summary (Month to Date) | Summary |
| VM Cost vs. Price &#124; VM Cost and Price Details | VM Cost vs. Price | Members of the Group (Select to View Trend) | List |
| VM Cost vs. Price &#124; VM Daily Cost and Price Trend | VM Cost vs. Price | Daily Cost and Daily Price | Trend |

## Reports
| Report Name |
|--|
| Showback (VM Cost) |
| Showback (vSphere Pod Cost) |
| Chargeback (VM Price) |

## Support

This dashboard requires vRealize Operation 8.2 Advanced or Enterprise edition or vRealize Operations Cloud.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-showback_and_chargeback/issues) for feedback.

## Changelog
2020-11-11
* Initial release
