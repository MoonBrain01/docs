.. _central_server_audits:

Server Audit Logs in Central
============================

As of `version 0.6 <https://github.com/getodk/central/releases/tag/v0.6.0-beta.0>`_, ODK Central tracks and logs audit actions for most administrative actions performed on the server. The following actions are logged:

 - **Project Actions**

   - Create
   - Update Details (name, settings, archival)
   - Delete

 - **Form Actions**

   - Create
   - Update Details (state, draft upload, publish action, settings)
   - Update Attachments
   - Delete

 - **Submission Actions**

   - Create
   - Update Metadata (review state)
   - Update Submission Data
   - Update Attachments

 - **Web User Actions**

   - Create
   - Update Details (display name, email, password)
   - Assign Role
   - Revoke Role
   - Retire

 - **App User Actions**

   - Create
   - Assign Role
   - Revoke Role
   - Revoke Access
   - Delete

 - **Public Link Actions**

   - Create
   - Assign Role
   - Revoke Role
   - Revoke Access
   - Delete

To access the audit logs, navigate to :guilabel:`System`, then select :guilabel:`Server Audit Logs` from the navigation menu that appears:

   .. image:: /img/central-server-audits/overview.png

Some details will sometimes appear in the :guilabel:`Details` column. The details view will be improved in future versions.

The table always defaults to only showing audit events from the current calendar day. To select a different date range, click on the date in the filter bar. A calendar will appear:

   .. image:: /img/central-server-audits/filter-date.png

You can click on two separate days to select a range of those days, or you can select a single day by clicking on it twice. Dates and times are always filtered and displayed according to the local time on the computer you are browsing the administration panel from.

You can also filter by the type of audit action instead. To do this, click on the dropdown to the left of the date, which by default is labeled :guilabel:`(All Actions)`.

   .. image:: /img/central-server-audits/filter-category.png

You can select a single action to filter by, or you can filter by an entire category (select :guilabel:`Form Actions` to see any action that pertains to Forms, for example.

