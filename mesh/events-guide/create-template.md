---
title: Create event template in Microsoft Mesh
description: Guide to creating a template for events in Microsoft Mesh
ms.service: mesh
author: typride
ms.author: tmilligan
ms.date: 10/05/2023
ms.topic: Guide
keywords: Microsoft Mesh, templates, events, hosting, event producer, event organizer, customize
---

# Create event template

Event templates allow organizers to reuse environments and customization made in environments for future events.

Event templates can be created directly in Microsoft Mesh app, or created from an existing Event.

## Event template creation flow

1. [**Create** your Event template directly](#create-event-template-in-microsoft-mesh) or [Create a template from an existing event](#create-event-template-from-an-existing-event).

1. **Customize** your Event template using the Customize event experience.

1. **Edit draft Event template** as much as you need to before publishing.

1. **Publish** the Event template to be reused in future events.

## Create Event template in Microsoft Mesh

1. In the Microsoft Mesh app, select the **Manage event templates** button.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-dashboard-creation-button.png" alt-text="Event template creation button in ":::

1. In this view, you can see the previous templates that have been created, see the draft templates, or create a new template.

    - **Published** Event templates cannot be edited further and can be used in Events.


    - **Draft** Event templates are a work-in-progress, can be customized, and can be used in Event.

    :::image type="content" source="../media/mesh-event-producer-guide/template-create-new.png" alt-text="Template create new mesh app":::

1. Select create new template and add your **Title**, **Description**, and select the **World location** for the template to exist in.

1. Select the environment that you want to use with your template. This could be a standard environment or a custom environment that was uploaded with the Mesh toolkit.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-environment-creation.png" alt-text="Environment selection in Microsoft Mesh app":::

1. Once your template is created, you should receive a notification that your Template was created.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-create-success.png" alt-text="Template creation success toast notification in Mesh":::

## Create Event template from an existing event

If you've already customized an event or prefer to create a template from an existing event, you can do that in the Mesh portal in the Event details page or the Environments page.

**Event details page:**

:::image type="content" source="../media/mesh-event-producer-guide/Event-create-save-as-event-template.png" alt-text="Screenshot of Mesh portal showing option to save an event as a template.":::

**Environments page:**

:::image type="content" source="../media/mesh-event-producer-guide/Create-event-template-from-environments-page.png" alt-text="Screenshot of Mesh portal Environments page, showing create Event template option.":::

## Customize your Event template

Now that your Event template was created, you can customize it with the Customize it. For more info how to customize see [Customize event experience](customize-event.md#customize-an-event-template).

1. Find your **Event template** draft.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-selection.png" alt-text="Screenshot of Mesh app Manage event templates window, draft events highlighted.":::

1. Select the **Customize event experience** button to start customizing the Event template.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-enter-customize-event-experience.png" alt-text="Screenshot of Mesh app, Customize event experience button highlighted.":::

## Publish your event template

Once you're happy with your customizations, **Publish** the Event template to be reused in future events.

1. In the draft section, you'll see the newly made template. Select the **options** button on the template and choose **Publish**.

    :::image type="content" source="../media/mesh-event-producer-guide/template-publish.png" alt-text="Template publish option in Mesh app":::

1. Your template should show in the published category.

    :::image type="content" source="../media/mesh-event-producer-guide/Template-published-final.png" alt-text="Template published final":::

## Use your template

1. Now, if you create an event and select Event template:

    :::image type="content" source="../media/mesh-event-producer-guide/Create-event-template-selection.png" alt-text="Template selection for an event.":::

1. Select the Mesh world where you created your event template.

    :::image type="content" source="../media/mesh-event-producer-guide/Create-event-template-world-selection.png" alt-text="Select world to use for your event":::

1. Find the template you created, and choose it, then select **Next**.

    :::image type="content" source="../media/mesh-event-producer-guide/Create-event-template-select-template.png" alt-text="Select template":::

Now your template is created and selected for your event. When creating another event, you can find it in the Mesh world it was created and used in any future event.

## Unpublish your template to customize again

Should you want to edit an Event Template again, you can unpublish your template to convert it to a draft form. Then you can customize it as desired, publish again, and reuse.

> [!div class="nextstepaction"]
> [Produce your event](produce-event.md)
