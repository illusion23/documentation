=============================
Create your own digest emails
=============================
To create your own Digest Email, navigate to your **Settings** App and proceed to :menuselection:`General Settings --> Statistics --> Digest Settings`. Click **--> Configure Digest Emails** and then click **Create**.

From there, give your Digest Email a title, specify periodicity, and choose your desired KPIs and recipients fields as needed. After you click **Save**, your new custom Digest Email will be available from the list under **Settings / Digest Emails** and in the dropdown menu on the General Settings screen.

Add custom KPIs with Odoo Studio
================================
For either *Your Odoo Periodic Digest* or your own custom Digest Email, you can add your own KPIs by using Odoo Studio.

To begin, click the **Toggle Studio** icon or click the **Recipients** tab and then the ellipses :menuselection:`… icon --> Add Custom Field` to edit the template or add additional fields.

In order to create additional fields, you must create 2 fields on the digest object:

#. first, create a boolean field called `kpi_myfield` and display it in the KPIs tab;
#. then create a computed field called `kpi_myfield_value` that will compute your customized KPI;
#. finally, select your KPI(s) in the KPIs tab.

Computed values reference table
-------------------------------
+-----------------------+-----------------------------------------+
| LABEL                 | VALUE                                   |
+-----------------------+-----------------------------------------+
| Connected Users       | kpi_res_users_connected_value           |
+-----------------------+-----------------------------------------+
| Messages Sent         | kpi_mail_message_total_value            |
+-----------------------+-----------------------------------------+
| New Leads             | kpi_mail_message_total_value            |
+-----------------------+-----------------------------------------+
| Opportunities Won     | kpi_crm_opportunities_won_value         |
+-----------------------+-----------------------------------------+
| Open Tasks            | kpi_project_task_opened_value           |
+-----------------------+-----------------------------------------+
| Tickets Closed        | kpi_helpdesk_tickets_closed_value       |
+-----------------------+-----------------------------------------+
| % of Happiness        | kpi_livechat_rating_value               |
+-----------------------+-----------------------------------------+
| Conversations handled | kpi_livechat_conversations_value        |
+-----------------------+-----------------------------------------+
| Time to answer (sec)  | kpi_livechat_response_value             |
+-----------------------+-----------------------------------------+
| All Sales             | kpi_all_sale_total_value                |
+-----------------------+-----------------------------------------+
| eCommerce Sales       | kpi_website_sale_total_value            |
+-----------------------+-----------------------------------------+
| Revenue               | kpi_account_total_revenue_value         |
+-----------------------+-----------------------------------------+
| Bank & Cash Moves     | kpi_account_bank_cash_value             |
+-----------------------+-----------------------------------------+
| POS Sales             | kpi_pos_total_value                     |
+-----------------------+-----------------------------------------+
| New Employees         | kpi_hr_recruitment_new_colleagues_value |
+-----------------------+-----------------------------------------+