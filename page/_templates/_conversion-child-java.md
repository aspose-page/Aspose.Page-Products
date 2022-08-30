---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: page
platformtag: java
feature: conversion
informat: {{i18n.informat}}
outformat: {{i18n.outformat}}
otherformats: {{i18n.otherformats}}
---

{{<meta path="/{{lang}}/meta/conversion/default.md" section="faqchild">}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}">}}

{{< blocks/products/pf/main-container pfName="Aspose.Page" subTitlepfName="for Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/page/aspose_page-for-java.svg" liveDemosLink="https://products.aspose.app/page/applications" PricingLink="https://purchase.aspose.com/pricing/page/java" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/page/java/" installationsDocsLink="https://docs.aspose.com/page/java/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Page/" nugetPackageName="Aspose.Page" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/page/java/" >}}

{{% blocks/products/pf/feature-page-summary h2="{{i18n.overview.title}}" %}}

<p>{{i18n.overview.p1}}</p>
<p>{{i18n.overview.p2}}</p>
<p>{{i18n.overview.p3}}</p>

-  <p>{{i18n.overview.p4}}</p>
-  <p>{{i18n.overview.p5}}</p>


{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

    <repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://repository.aspose.com/repo/</url>
    </repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
    <dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-page</artifactId>
    <version>version of aspose-page API</version>
    <classifier>jdk17</classifier>
    </dependency>

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

{{< highlight java >}}
    // initialize PostScript input stream
    FileInputStream psStream = new FileInputStream("input.{{i18n.informat lower}}");

    // load {{i18n.informat}} document
    PsDocument document = new PsDocument(psStream);

    //create an instance of {{i18n.outformat}}SaveOptions
    {{i18n.outformat}}SaveOptions options = new {{i18n.outformat}}SaveOptions();
    //create rendering device for {{i18n.informat}} format
    ImageDevice device = new ImageDevice();
    //save {{i18n.informat}} as {{i18n.outformat}}
    document.save(device, options);
    {{< /highlight >}} 

{{% /blocks/products/pf/agp/code-autogen %}}

{{< blocks/products/pf/agp/demobox sectionTitle="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.title">}}" sectionDescription="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.overview">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.p1">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.p2">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.p3">}}" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="{{<import path="/{{lang}}/partials/_content.md" section="widgetbackup.p4">}}" >}}
{{< /blocks/products/pf/agp/demobox >}}


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