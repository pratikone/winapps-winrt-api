---
-api-id: T:Microsoft.UI.Xaml.Controls.Expander
-api-type: winrt class
---

# Microsoft.UI.Xaml.Controls.Expander

<!--
public class Expander : Windows.UI.Xaml.Controls.ContentControl
-->

## -description

::: moniker range="winui-3.0-preview"
> [!CAUTION]
> This API is in development and considered experimental in the WinUI version selected. It might be altered or unavailable in other versions.
::: moniker-end

Represents a control that displays a header and has a collapsible body that displays content.

## -remarks

> [!TIP]
> For more info, design guidance, and code examples, see [Expander overview](/windows/apps/design/controls/expander).

Use an `Expander` to focus on the most important content when display space is limited. The `Expander` control lets you show or hide less important content that's related to a piece of primary content that's always visible. Items contained in the [Header](/uwp/api/microsoft.ui.xaml.controls.expander.header) are always visible. The user can expand and collapse the [Content](contentcontrol_content.md) area, where secondary content is displayed, by interacting with the header. When the content area is expanded, it pushes other UI elements out of the way; it does not overlay other UI. The `Expander` can expand upwards or downwards.

Both the `Header` and `Content` areas can contain any content, from simple text to complex UI layouts.

### Control style and template

You can modify the default [Style](../microsoft.ui.xaml/style.md) and [ControlTemplate](controltemplate.md) to give the control a unique appearance. For information about modifying a control's style and template, see [XAML styles](/windows/apps/design/style/xaml-styles). XAML also includes resources that you can use to modify the colors of a control in different visual states without modifying the control template. Modifying these resources is preferred to setting properties such as [Background](control_background.md) and [Foreground](control_foreground.md). For more info, see the [Light-weight styling](/windows/apps/design/style/xaml-styles#lightweight-styling) section of the [XAML styles](/windows/apps/design/style/xaml-styles) article.

The resources for this control are listed in the [ThemeDictionaries](/windows/apps/design/style/xaml-theme-resources) section of the [Expander_themeresources.xaml](https://github.com/microsoft/microsoft-ui-xaml/blob/main/dev/Expander/Expander_themeresources.xaml) file on GitHub. The `ResourceKey` value for each `StaticResource` references a brush and color in the [Common_themeresources_any.xaml](https://github.com/microsoft/microsoft-ui-xaml/blob/main/dev/CommonStyles/Common_themeresources_any.xaml) file.

## -see-also

[Expander overview](/windows/apps/design/controls/expander)

## -examples

> [!TIP]
> For more info, design guidance, and code examples, see [Expander](/windows/apps/design/controls/expander).

> [!div class="nextstepaction"]
> [Open the WinUI 3 Gallery app and see the Expander in action](winui3gallery:/item/Expander).

> The **WinUI 3 Gallery** app includes interactive examples of most WinUI 3 controls, features, and functionality. Get the app from the [Microsoft Store](https://www.microsoft.com/store/productId/9P3JFPWWDZRC) or get the source code on [GitHub](https://github.com/microsoft/WinUI-Gallery).
