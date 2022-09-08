---
title: Sending e-mail notifications
description: The notification module enables you to create and send e-mail notifications easily.
---

## Overview

In Kuroco, you can create periodic notifications (such as newsletters) using the Notification module. Each entry or issue is called a "message", which can be managed through the Messages sub-module. 

This tutorial explains the full delivery workflow of a simple e-newsletter issue.

## What you'll learn

After completing this tutorial, you will know how to:
- [Create a period notification](#creating-a-notification)
- [Set and verify the mailing list](#specifying-the-default-recipients)
- [Add a new entry to the periodic notification](#composing-a-new-message)
- [Schedule the delivery for a set date and time](#scheduled-delivery)
- [Verify notification statuses](#verifying-the-delivery-status)

## Before you start

For this tutorial, we will be adding recipients to our mailing list from a custom member filter.     
Create a filter called "Premium members" in advance. A detailed guide on how to do this can be found in [Tutorial: Using custom member filters](/docs/tutorials/using-custom-member-filters/).

## Creating a notification 

In the sidebar menu, select [Campaign] -> [Notification].

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/25ee5c4725c006c9b733db13aad32e0c.png)](https://diverta.gyazo.com/25ee5c4725c006c9b733db13aad32e0c)

On the Notification list screen, click [Add] in the upper right corner.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/911c80339eb06376e258108d46675c7f.png)](https://diverta.gyazo.com/911c80339eb06376e258108d46675c7f)

For demo purposes, we will create a periodic notification called "Kuroco newsletter".   
Fill in the following information in the editor:

| Field | Sub-field | Value |
| :--- | :--- | :--- |
| Name | | `Kuroco newsletter` |
| Information | | Enter a short description of your notification (optional). |
| Sender | E-mail address | Enter your "From" e-mail here (default = `noreply@kuroco-mail.app`). |

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/3fb5117f85e76cf7ef8916399c7f588e.png)](https://diverta.gyazo.com/3fb5117f85e76cf7ef8916399c7f588e)

Click [Add] at the bottom of the screen.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/107fc500bb1d63e1b5e742ada388e834.png)](https://diverta.gyazo.com/107fc500bb1d63e1b5e742ada388e834)

## Specifying the default recipients

Next, set the recipients of this notification series.

### With the subscriber list

Click the [Subscribers] tab.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/9aef64a3aadc6a3433b0ac2474b754df.png)](https://diverta.gyazo.com/9aef64a3aadc6a3433b0ac2474b754df)

On the Subscribers screen, enter the member ID or e-mail (if member ID is not available) of the recipient and click [Add].

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/29b9cfa6d24fa57da9ea443f12bca149.gif)](https://diverta.gyazo.com/29b9cfa6d24fa57da9ea443f12bca149)

Verify the new entry in the notification subscriber list at the bottom.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/a8455720d8acd719fca867d60808f581.png)](https://diverta.gyazo.com/a8455720d8acd719fca867d60808f581)

Now, go back to the [Basic settings] tab.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/cfb779ed8e7d3e1d9e9652f7f89c00e3.png)](https://diverta.gyazo.com/cfb779ed8e7d3e1d9e9652f7f89c00e3)

In "Default recipients", select "Send to subscribers".

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/187863aaf2e82353062272d7394ae448.png)](https://diverta.gyazo.com/187863aaf2e82353062272d7394ae448)

### With a custom member filter

In "Default recipients" of the Basic settings tab, select "Premium members" from the dropdown list on the right.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/7bce71bb467603d3432be9dc7a62a0f7.png)](https://diverta.gyazo.com/7bce71bb467603d3432be9dc7a62a0f7)

Click [Set recipient(s)]. The filter name will appear under <<Recipients>> on the left.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/6bbd0fe7a295c35b37e4e236a6204212.gif)](https://diverta.gyazo.com/6bbd0fe7a295c35b37e4e236a6204212)

### Verifying the mailing list

Click [Verify recipients] to view the recipients' e-mail addresses.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/5ab6dd04bccc1e6988edc2bb70109025.png)](https://diverta.gyazo.com/5ab6dd04bccc1e6988edc2bb70109025)

If there are no errors, click [Update] to save the settings.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/b4c1ebb9ab6ff4dd680aad4d9e3b8190.png)](https://diverta.gyazo.com/b4c1ebb9ab6ff4dd680aad4d9e3b8190)

[[info]] If a selected recipient does not appear in the list, verify if "Don't subscribe to notifications" is unchecked on their [Member editor page](https://t.gyazo.com/teams/diverta/ee9094114973475095bcba4744210464.png). For more information, see [User guide: Member editor](/docs/management/member/#member-editor).

## Composing a new message

Next, add a new entry to your newsletter.    
In the notification editor, click the [Messages] tab.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/5abba60de2a13d906069ad06aec7d380.png)](https://diverta.gyazo.com/5abba60de2a13d906069ad06aec7d380)

On the Messages screen, click [Add] in the upper right corner.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/956371c04756678c69e436549ce94183.png)](https://diverta.gyazo.com/956371c04756678c69e436549ce94183)

Fill in the required fields in the Message editor. (For a detailed explanation of each field, see [User guide: Notification messages](/docs/management/composing-new-notification-emails/).)

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/8826663299091acd269cfb26854796e4.png)](https://diverta.gyazo.com/8826663299091acd269cfb26854796e4)
[![Image from Gyazo](https://t.gyazo.com/teams/diverta/335ee878ae76b36ca022040e5a14e146.png)](https://diverta.gyazo.com/335ee878ae76b36ca022040e5a14e146)

Under "Send test", you can enter your own e-mail address and click [Send test] to see a sample of the newsletter issue that will be delivered.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/19018bb7a5df6b9b4fb12986a947dc86.png)](https://diverta.gyazo.com/19018bb7a5df6b9b4fb12986a947dc86)
[![Image from Gyazo](https://t.gyazo.com/teams/diverta/60a7738d671c6336781feb3114fb3027.png)](https://diverta.gyazo.com/60a7738d671c6336781feb3114fb3027)

When you are done, click [Save as pending].

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/f06c68090c2fc8623ad458b4b2d28686.png)](https://diverta.gyazo.com/f06c68090c2fc8623ad458b4b2d28686)

You will receive a confirmation prompt. Click [Yes]. The notification will be sent out to your mailing list.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/85e87a34d52c1855bdc0870fe0cefc1a.png)](https://diverta.gyazo.com/85e87a34d52c1855bdc0870fe0cefc1a)

### Scheduled delivery

In the above example, we selected "Send now" in "Send date and time" to dispatch the notification message immediately after saving it. Alternatively, you can schedule the delivery by manually setting the date and time.

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/b7ffad575d89ca4c30ac73d048fa2ea9.png)](https://diverta.gyazo.com/b7ffad575d89ca4c30ac73d048fa2ea9)

Then, edit your message as usual and click [Save as pending]. 

## Verifying the delivery status

You can verify the statuses of all the messages in a notification on the Messages screen.    

[![Image from Gyazo](https://t.gyazo.com/teams/diverta/41d31556e5fee0c0a2a9fa4238be77eb.png)](https://diverta.gyazo.com/41d31556e5fee0c0a2a9fa4238be77eb)

## More information

- [User guide: Notification - Basic settings](/docs/management/notification-basic-settings/)
- [User guide: Notification - Messages](/docs/management/notification-sent-messages/)
- [User guide: Notification - Message editor](/docs/management/composing-new-notification-emails/)
- [Tutorial: Registering notification subscribers](/docs/tutorials/how-to-register-subscribers-on-magazine/)
- [Tutorial: Using custom member filters](/docs/tutorials/using-custom-member-filters/)
