---
title: Build apps for the Microsoft Teams platform
author: heath-hamilton
description: Get an overview of how developers can extend Microsoft Teams features with custom apps.
ms.topic: overview
ms.localizationpriority: medium
ms.author: lajanuar
ms.date: 05/24/2021
---
# Build apps for Microsoft Teams

Microsoft Teams apps bring key information, common tools, and trusted processes to where people increasingly gather, learn, and work.

Apps are how you extend Teams to fit your needs. Create something brand new for Teams or integrate an existing app.

> [!div class="nextstepaction"]
> [Start here](get-started/prerequisites.md)

## What are Teams apps?

Teams apps are a combination of [capabilities](concepts/capabilities-overview.md). Some apps are simple (send notifications), while others are complex (manage patient records). When planning your app, remember that Teams is a collaboration hub. The best Teams apps help people express themselves and work better together.

### Personal apps

:::row:::
   :::column span="1":::

**Help people focus**: A [personal app](concepts/design/personal-apps.md) is a dedicated space or bot to help users focus on their own tasks or view activities important to them.

   :::column-end:::

   :::column span="3":::

:::image type="content" source="assets/images/overview-personal-apps-2021.png" alt-text="Conceptual representation of what personal apps look like in the Teams client." border="false":::

   :::column-end:::

:::row-end:::

### Tabs

:::row:::
   :::column span="1":::

**Collaborate more conveniently**: Display your web-based content in a [tab](tabs/what-are-tabs.md) where people can discuss and work on it together.

   :::column-end:::

   :::column span="3":::

:::image type="content" source="assets/images/overview-channel-chat-apps-2021.png" alt-text="Conceptual representation of what tabs look like in the Teams client." border="false":::

   :::column-end:::

:::row-end:::

### Bots

:::row:::
   :::column span="1":::

**Turn words into actions**: Conversations often result in the need to do something (generate an order, review my code, check ticket status, and so on). A [bot](bots/what-are-bots.md) can kick off these kinds of workflows right inside Teams.

   :::column-end:::

   :::column span="3":::

:::image type="content" source="assets/images/overview-bots-2021.png" alt-text="Conceptual representation of what bots look like in the Teams client." border="false":::

   :::column-end:::

:::row-end:::

### Messaging extensions

:::row:::

   :::column span="1":::

**Make it easier to multitask**: With [messaging extensions](messaging-extensions/what-are-messaging-extensions.md), you can quickly share external information in a conversation. You also can act on a message, such as creating a help ticket based on the content of a channel post.

   :::column-end:::

   :::column span="3":::

:::image type="content" source="assets/images/overview-messaging-extensions-2021.png" alt-text="Conceptual representation of what messaging extensions look like in the Teams client." border="false":::

   :::column-end:::
:::row-end:::

### Meeting extensions

:::row:::

   :::column span="1":::

**Create apps for meetings**: There are a few options for [incorporating your app into the Teams calling experience](apps-in-teams-meetings/design/designing-apps-in-meetings.md).

   :::column-end:::

   :::column span="3":::

:::image type="content" source="assets/images/overview-meeting-extensions-2021.png" alt-text="Conceptual representation of what meeting extensions look like in the Teams client." border="false":::

   :::column-end:::
:::row-end:::

### Webhooks and connectors

:::row:::

   :::column span="":::

**Communicate with external apps**: [Incoming webhooks](webhooks-and-connectors/what-are-webhooks-and-connectors.md#incoming-webhooks) are a simple way to automatically send notifications from another app to a Teams channel. With [outgoing webhooks](webhooks-and-connectors/what-are-webhooks-and-connectors.md#outgoing-webhooks), message your web service with an @mention.

   :::column-end:::

   :::column span="":::

:::image type="content" source="assets/images/overview-connectors.png" alt-text="Conceptual representation of what connectors look like in the Teams client." border="false":::

   :::column-end:::
:::row-end:::

### Microsoft Graph for Teams

:::row:::

   :::column span="":::

**Utilize Teams data**: The [Microsoft Graph API for Teams](/graph/teams-concept-overview) provides access to information about teams, channels, users, and messages that can help you create or enhance features for your app (such as rich notifications).

   :::column-end:::

   :::column span="":::

:::image type="content" source="assets/images/overview-graph.png" alt-text="Conceptual representation of the Microsoft Graph API for Teams." border="false":::

   :::column-end:::
:::row-end:::

:::row:::
   :::column span="2":::

## Start building

Quickly familiarize yourself with building for Teams by setting up your environment and creating a simple app.

> [!div class="nextstepaction"]
> [Build your first app](get-started/prerequisites.md)

   :::column-end:::
   :::column span="":::

   :::column-end:::
:::row-end:::

:::row:::
   :::column span="2":::

## Integrate with Teams

Blend the features users love about an existing web app, service, or system with the collaborative features of Teams.

> [!div class="nextstepaction"]
> [Integrate an existing app](samples/integrating-web-apps.md)

   :::column-end:::
   :::column span="":::

   :::column-end:::
:::row-end:::

:::row:::
   :::column span="2":::

## A little code goes a long way

You don't need to be an expert programmer to build a great Teams app. Try one of several low-code solutions.

> [!div class="nextstepaction"]
> [Create a low-code app](samples/teams-low-code-solutions.md)

   :::column-end:::
   :::column span="":::

   :::column-end:::
:::row-end:::

:::row:::
   :::column span="2":::

## Get ideas for your app

Looking for app development inspiration? Browse our list of real-world scenarios and industry solutions with high fidelity concept mocks to understand the various ways Teams apps can help your users.

> [!div class="nextstepaction"]
> [See app scenarios](https://adoption.microsoft.com/extensibility-look-book/scenarios/)

   :::column-end:::
   :::column span="":::

   :::column-end:::
:::row-end:::

## Integrate Teams in your external app
This page focuses on embedding your own experiences into Microsoft Teams by building Teams apps. If you'd like to *reverse* this model and integrate Teams or other communication capabilities into your own external app experience, see [Azure Communication Services](/azure/communication-services/overview). Azure Communication Services are cloud-based services with REST APIs and client library SDKs to help you integrate communication into your own custom applications. You can embed generic or Teams-styled React Web components for calling and chat with the help of the [UI library](https://azure.github.io/communication-ui-library/).

Azure Communication Services applications can use public preview functionality to [interoperate with Teams](/azure/communication-services/concepts/teams-interop) and enable your custom application to join Teams meetings anonymously. For example, you can integrate video calling into a mobile banking application and allow end-users to virtually meet with bank employees using Microsoft Teams. 

You can also integrate Microsoft 365 identity to build external applications that embed video and PSTN calling on behalf of a Teams user. If you've used [Skype for Business SDKs](/skype-sdk/appsdk/skypeappsdk) in the past, these capabilities as part of Azure Communication Services are recommended as a replacement.

## See also

* [Add a Share-to-Teams button to your website](concepts/build-and-test/share-to-teams.md)
* [Design your Teams app](concepts/design/design-teams-app-overview.md)
* [Microsoft Teams JavaScript client SDK](/javascript/api/@microsoft/teams-js/?view=msteams-client-js-latest&preserve-view=true)
* Bot Framework SDK for [JavaScript](https://github.com/Microsoft/botbuilder-js) and [.NET](https://github.com/Microsoft/botbuilder-dotnet/)
* [Distribute your Teams app](concepts/deploy-and-publish/apps-publish-overview.md)
