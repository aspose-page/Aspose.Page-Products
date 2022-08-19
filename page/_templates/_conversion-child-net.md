---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: page
platformtag: net
feature: conversion
informat: {{i18n.informat}}
outformat: {{i18n.outformat}}
otherformats: {{i18n.otherformats}}
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

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature2.title}}" %}}

<p>{{i18n.feature2.item1}}</p>

-  {{i18n.feature2.item2}}
-  {{i18n.feature2.item3}}
-  {{i18n.feature2.item4}}

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/code-autogen title="{{i18n.gist.p2}}" gistPath="" %}}

{{< highlight csharp >}}
    // create a stream for input {{i18n.informat}} file
    using (var psStream = new System.IO.FileStream("template.{{i18n.informat}}", System.IO.FileMode.Create, System.IO.FileAccess.Read))
    {
        // create a stream for output {{i18n.outformat}} file
        using (var pdfStream = System.IO.File.Open("output.gif", System.IO.FileMode.Open, System.IO.FileAccess.Write))
        {
            // load the {{i18n.informat}} file from stream
            var document = new Aspose.Page.{{i18n.informat}}.PsDocument(psStream);
            // create an instance of ImageSaveOptions
            var options = new Aspose.Page.{{i18n.informat}}.Device.ImageSaveOptions();
            // create rendering device for {{i18n.outformat}}
            var device = new Aspose.Page.{{i18n.informat}}.Device.ImageDevice(System.Drawing.Imaging.ImageFormat.{{i18n.outformat}});
            // save {{i18n.informat}} as {{i18n.outformat}}
            document.Save(device, options);
        }
    }
{{< /highlight >}} 

{{% /blocks/products/pf/agp/code-autogen %}}


{{< blocks/products/pf/agp/about-file-section >}}     
{{< blocks/products/pf/agp/about-file-text fileFormat="{{i18n.informat}}" section="{{i18n.informat}}" >}}
{{<import path="/{{lang}}/partials/_formats.md" section="{{i18n.informat}}">}}
{{< /blocks/products/pf/agp/about-file-text >}}

{{< blocks/products/pf/agp/about-file-text fileFormat="{{i18n.outformat}}" section="{{i18n.outformat}}" >}}
{{<import path="/{{lang}}/partials/_formats.md" section="{{i18n.outformat}}">}}
{{< /blocks/products/pf/agp/about-file-text >}} 
{{< /blocks/products/pf/agp/about-file-section >}}	


{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class>}} 