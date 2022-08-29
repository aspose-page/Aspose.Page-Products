---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: page
platformtag: net
feature: signature
informat: {{i18n.informat}}
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}">}}

{{< blocks/products/pf/main-container pfName="Aspose.Page" subTitlepfName="for .NET" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/page/aspose_page-for-net.svg" liveDemosLink="https://products.aspose.app/page/applications" PricingLink="https://purchase.aspose.com/pricing/page/net" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/page/net/" installationsDocsLink="https://docs.aspose.com/page/net/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Page/" nugetPackageName="Aspose.Page" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/page/net/" >}}

{{% blocks/products/pf/feature-page-summary h2="{{i18n.overview.title}}" %}}

<p>{{i18n.overview.p1}}</p>
<p>{{i18n.overview.p2}}</p>
<p>{{i18n.overview.p3}}</p>

-  <p>{{i18n.overview.p4}}</p>
-  <p>{{i18n.overview.p5}}</p>

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

    PM> Install-Package Aspose.Page

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/feature-page-summary %}}


{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature1.title}}" %}}

<p>{{i18n.feature1.item1}}</p>

1. {{i18n.feature1.item2}}
2. {{i18n.feature1.item3}}
3. {{i18n.feature1.item4}}
4. {{i18n.feature1.item5}}

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature2.title}}" %}}

<p>{{i18n.feature2.item1}}</p>

-  {{i18n.feature2.item2}}
-  {{i18n.feature2.item3}}
-  {{i18n.feature2.item4}}

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/code-autogen title="{{i18n.gist.p2}}" gistPath="" %}}

{{< highlight csharp >}}
    XpsDocument document = new XpsDocument();

    XpsSolidColorBrush textFill = document.CreateSolidColorBrush(Color.Black);
			
    textFill = document.CreateSolidColorBrush(Color.Black);
    //Add glyph to the document
    XpsGlyphs glyphs = document.AddGlyphs("Arial", 24, FontStyle.Regular, 450f, 50f, "eSignature Text");
    glyphs.Fill = textFill;

    document.Save("outPath.xps");  
{{< /highlight >}} 

{{% /blocks/products/pf/agp/code-autogen %}}

{{< blocks/products/pf/agp/demobox sectionTitle="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.title">}}" sectionDescription="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.overview">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.p1">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.p2">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.p3">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupsign.p4">}}" >}}
{{< /blocks/products/pf/agp/demobox >}}


{{< blocks/products/pf/agp/about-file-section >}}     
{{< blocks/products/pf/agp/about-file-text fileFormat="{{i18n.informat}}" section="{{i18n.informat}}" >}}
{{<import path="/{{lang}}/partials/_formats.md" section="{{i18n.informat}}">}}
{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class>}} 