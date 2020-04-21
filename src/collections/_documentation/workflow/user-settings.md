---
title: User Settings
sidebar_order: 8
---
Manage your personal account details from the *User Settings* page, available in the dropdown menu under your organization’s name.

## Account Details

All changes in this section are saved automatically.

## Name

Change the name displayed next to your avatar by editing the *Name* field.

[{% asset user-settings/us-name.png alt="Name field in Account Details under User Settings" width="217.5" %}]({% asset user-settings/us-name.png @path %})

## Preferences

### Stack trace Order

Choose the default ordering of frames in stack traces. By default, this order is set to let Sentry decide. 

[{% asset user-settings/us-sto.png alt="Stack trace order field in Account Details under User Settings" width="617.5" %}]({% asset user-settings/us-sto.png @path %})

### Language

Choose the default language used in your Dashboard from the dropdown.

[{% asset user-settings/us-lang.png alt="Language field in Account Details under User Settings" width="221.5" %}]({% asset user-settings/us-lang.png @path %})

### Timezone

Issues' timestamps will be displayed in the timezone specified by this dropdown. For a 24-hour clock, click on the switch.

[{% asset user-settings/us-time.png alt="Timezone field in Account Details under User Settings" width="392" %}]({% asset user-settings/us-time.png @path %})

### Avatar

Choose fbetween displaying your Initials, an Image or a Gravatar next to your name. To save your selection, click *Save Avatar*.

[{% asset user-settings/us-avatar.png alt="Avatar field in Account Details under User Settings" width="227.5" %}]({% asset user-settings/us-avatar.png @path %})


# Security

The Security section is divided in two tabs: *Settings* and *Session History*.

## Settings
### Password

We recommend changing your password frequently. However, keep in mind that changing your password will invalidate all logged in sessions.

[{% asset user-settings/us-pass.png alt="Password field in Security under User Settings" width="516.5" %}]({% asset user-settings/us-pass.png @path %})

### Sessions

To sign out of all devices, click the *Sign out of all devices* button.

[{% asset user-settings/us-sess.png alt="Sessions field in Security under User Settings" width="653" %}]({% asset user-settings/us-sess.png @path %})

### Two-Factor Authentication

Keep your account information secure by enabling a two-factor authentication method. Choose between an Authenticator App, Text Message or an U2F hardware device.

[{% asset user-settings/us-2fact.png alt="Two-Factor Authentication selection in Securty under User Settings" width="930" %}]({% asset user-settings/us-2fact.png @path %})

### Recover Codes

Use recovery codes to access your account if you lose your device and cannot receive two-factor authentication codes. Click the *View Codes* button to download, print or copy your codes to a secure location.

[{% asset user-settings/us-rec.png alt="Recover codes field in Security under User Settings" width="927" %}]({% asset user-settings/us-rec.png @path %})

### Session History

A historical list of sessions, including First Seen and Last Seen timestamps, can be found under the Session History tab.

[{% asset user-settings/us-shistory.png alt="Session History tab in Security under User Settings" width="483" %}]({% asset user-settings/us-shistory.png @path %})

# Notifications

The Notifications section includes options to customize alerts, email routing, weekly reports, and notifications for workflow, deploy and activity. 

## Alerts

While Project Alerts are defined in *Project Settings*, you can enable *Send Me Alerts* to receive alerts sent to your teams and fine-tuning the ones you receive per project. 

[{% asset user-settings/us-alert.png alt="Alerts field in Notifications under User Settings" width="570" %}]({% asset user-settings/us-alert.png @path %})

## Workflow Notifications

Control workflow notifications like changes in issue assignment, resolution status, and comments by enabling *Send Me Workflow Notifications* and fine-tuning them per project. 

[{% asset user-settings/us-work.png alt="Workflow selection in Notifications under User Settings" width="776" %}]({% asset user-settings/us-work.png @path %})

## Email Routing

Route email notifications to an alternative email address and keep your project notifications organized. 

[{% asset user-settings/us-eroute.png alt="Email Routing field in Notifications under User Settings" width="509.5" %}]({% asset user-settings/us-eroute.png @path %})

## Weekly Reports

Reports are generated per project and sent once a week.  

[{% asset user-settings/us-wrfield.png alt="Weekly Reports field in Notifications under User Settings" width="552.5" %}]({% asset user-settings/us-wrfield.png @path %})

The following report sample shows details on *Events Seen This Week*, *Events by Issue Type*, *Events by Project* and activity over time.

[{% asset user-settings/us-ereport.png alt="Weekly Report email sample" width="631.5" %}]({% asset user-settings/us-ereport.png @path %})

## Deploy Notifications

To keep track of deployment details like release version, environments and commit reviews, select *On* and choose an option from the dropdown next to each organization.

[{% asset user-settings/us-deploy.png alt="Deploy Notifications selection in Notifications under User Settings" width="841" %}]({% asset user-settings/us-deploy.png @path %})

## My Activity

Updates regarding your user account actions, such as claiming unassigned issues previously resolved, can be turned into an email notification in this section.

[{% asset user-settings/us-myact.png alt="My Activity selection in Notifications under User Settings" width="563" %}]({% asset user-settings/us-myact.png @path %})

{% capture __alert_content -%}
A shortcut to the Emails panel can be found at the bottom of this section.

{% asset user-settings/us-npanellink.png alt="A link to the Email panel in Notifications under My Activity" %}

{%- endcapture -%}
{%- include components/alert.html
    title="Note"
    content=__alert_content
%}

## Emails

The email address used to login to your Sentry account is by default your primary email address. An additional email address can be added under the *Add Secondary Emails* section.

[{% asset user-settings/us-eprime.png alt="Primary email field in Emails under User Settings" %}]({% asset user-settings/us-eprime.png @path %})

{% capture __alert_content -%}

A shortcut to the *Notifications* panel can be found at the bottom of this section. 

{% asset user-settings/us-epanellink.png alt="A link to the Notifications panel in Emails under Additional Email" %}

{%- endcapture -%}
{%- include components/alert.html
    title="Note"
    content=__alert_content
%}

## Subscriptions

As part of our compliance with the EU’s General Data Protection Regulation (GDPR), you would only receive marketing campaign emails after explicitly opting-in to any of the listed categories. 

[{% asset user-settings/us-subs.png alt="Subscriptions section under User Settings" %}]({% asset user-settings/us-subs.png @path %})

## Authorized Applications

All authorized third-party applications are listed in this section. Authentication tokens are required for authorization and can be found in the [*Auth Tokens*](https://sentry.io/api/) section. 

## Identities

We integrate with several identity providers, like Okta, OneLogin, Auth0, and Yubico. To disconnect any previously configured provider, click the *Disconnect* button.

[{% asset user-settings/us-id.png alt="Disconnect button in Identities section under User Settings" %}]({% asset user-settings/us-id.png @path %})

## Close Account

Closing your Sentry account automatically removes all data associated with your account. If your account is the sole owner of an organization, this organization will be deleted. Organizations with multiple owners will remain unchanged.

[{% asset user-settings/us-close.png alt="Close Account button in Close Account section under User Settings" %}]({% asset user-settings/us-close.png @path %})

{% capture __alert_content -%}

Deleting your account can not be undone. 

{%- endcapture -%}
{%- include components/alert.html
    title="Warning"
    content=__alert_content
    level="warning"
%}

## API

### Applications

Integrating your application with Sentry allows you to automatically send events to your Sentry instance. To create an application, click the *Create New Application* button.

[{% asset user-settings/us-apps.png alt="Create New Application button in the Applications section under User Settings" %}]({% asset user-settings/us-apps.png @path %})

### Auth Tokens

Authentication tokens allow you to perform actions against the Sentry API on behalf of your account. To create one, click the *Create New Token* button.

[{% asset user-settings/us-token.png alt="Create New Token button in the Auth Tokens section under User Settings" width="473.5" %}]({% asset user-settings/us-token.png @path %})