---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: page
platformtag: net
feature: viewer
informat: {{i18n.informat}}
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
    string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".pdf";
    // create a stream for input {{i18n.informat}} file
    using (var psStream = new System.IO.FileStream("template.{{i18n.informat lower}}", System.IO.FileMode.Create, System.IO.FileAccess.Read))
    {
        // create a stream for output PDF file
        using (var pdfStream = System.IO.File.Open(output, System.IO.FileMode.Open, System.IO.FileAccess.Write))
        {
            // load the {{i18n.informat}} file from stream
            var document = new Aspose.Page.{{i18n.informat}}.PsDocument(psStream);
            // create an instance of PdfSaveOptions
            var options = new Aspose.Page.{{i18n.informat}}.Device.PdfSaveOptions();
            // create PDF rendering device for {{i18n.informat}}
            var device = new Aspose.Page.{{i18n.informat}}.Device.PdfDevice(pdfStream);
            // save {{i18n.informat}} as PDF
            ocument.Save(device, options);
        }
    }
    // load resultant PDF in default application
    System.Diagnostics.Process.Start(output);
{{< /highlight >}} 

{{% /blocks/products/pf/agp/code-autogen %}}

{{< blocks/products/pf/agp/demobox sectionTitle="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.title">}}" sectionDescription="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.overview">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.p1">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.p2">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.p3">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackupview.p4">}}" >}}
{{< /blocks/products/pf/agp/demobox >}}

{{< blocks/products/pf/agp/other-supported-section title="{{i18n.otherformats.p1}}" subTitle="{{i18n.otherformats.p2}}" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/page/net/viewer/xps/" name="XPS" description="XML Paper Specifications" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/page/net/viewer/ps/" name="PS" description="Postscript" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/page/net/viewer/ps/" name="EPS" description="Encapsukated Postscript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}


{{< blocks/products/pf/agp/about-file-section >}}     
{{< blocks/products/pf/agp/about-file-text fileFormat="{{i18n.informat}}" section="{{i18n.informat}}" >}}
{{<import path="/{{lang}}/partials/_formats.md" section="{{i18n.informat}}">}}
{{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class>}} 