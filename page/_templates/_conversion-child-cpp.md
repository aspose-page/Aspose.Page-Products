---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: page
platformtag: cpp
feature: conversion
informat: {{i18n.informat}}
outformat: {{i18n.outformat}}
otherformats: {{i18n.otherformats}}
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}">}}

{{< blocks/products/pf/main-container pfName="Aspose.Page" subTitlepfName="for C++" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/page/aspose_page-for-cpp.svg" liveDemosLink="https://products.aspose.app/page/applications" PricingLink="https://purchase.aspose.com/pricing/page/cpp" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/page/cpp/" installationsDocsLink="https://docs.aspose.com/page/cpp/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Page/" nugetPackageName="Aspose.Page" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/page/cpp/" >}}

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

{{% /blocks/products/pf/agp/feature-section-col %}}


{{% blocks/products/pf/agp/code-autogen title="{{i18n.gist.p2}}" gistPath="" %}}


{{< highlight java >}}
    System::SharedPtr<System::Drawing::Imaging::ImageFormat> imageFormat = System::Drawing::Imaging::ImageFormat::get_{{i18n.outformat}}();

    System::SharedPtr<System::IO::FileStream> epsStream = System::MakeObject<System::IO::FileStream>(u"sourceFile.eps", System::IO::FileMode::Open, System::IO::FileAccess::Read);

    System::SharedPtr<{{i18n.informat}}Document> document = System::MakeObject<EpsDocument>({{i18n.informat lower}}Stream);

    // If you want to convert Postscript file despite of minor errors set this flag
    bool suppressErrors = true;

    //Initialize options object with necessary parameters.
    System::SharedPtr<ImageSaveOptions> options = System::MakeObject<ImageSaveOptions>(suppressErrors);

    System::SharedPtr<Aspose::Page::{{i18n.informat}}::Device::ImageDevice> device = System::MakeObject<Aspose::Page::{{i18n.informat}}::Device::ImageDevice>();

	    auto __finally_guard_0 = ::System::MakeScopeGuard([&epsStream]()
	    {
		    psStream->Close();
	    });

	    try{
		    document->Save(device, options);
	    }catch (...){
		    throw;
	    }
    System::ArrayPtr<System::ArrayPtr<uint8_t>> imagesBytes = device->get_ImagesBytes();
    //loop through each imagesBytes and write via file stream
{{< /highlight >}} 


{{% /blocks/products/pf/agp/code-autogen %}}

{{< blocks/products/pf/agp/demobox sectionTitle="{{i18n.informat}} to {{i18n.outformat}} Conversion Live Demos" sectionDescription="[Convert {{i18n.informat}} to {{i18n.outformat}}](https://products.aspose.app/page/conversion/{{i18n.informat lower}}-to-{{i18n.outformat lower}}) right now by visiting our Live Demos website." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your {{i18n.informat}} file, it will be converted instantly to {{i18n.outformat}}." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="C++ Page Document Manipulation Library" %}}

    {{% /blocks/products/pf/agp/content %}}

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