---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Signature"
product_tag: "signature"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Signature Cloud SDK for PDF Word Excel PPTX & Images"
head_description: "Java Cloud SDK for adding digital signature to documents and images. Use REST API to electronically sign PDF, Word, Excel, presentations."

############################# Header ############################
title: "eSignature Java Cloud SDK to Sign Documents"
description: "Develop top-quality tools for creating & managing digital signatures of many types via REST API. Secure files of popular formats."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Signature Cloud SDK for Java"
        image: "/sdk/272x272/groupdocs_signature-for-java.webp"
        product: "GroupDocs.Signature"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Overview"

            # button loop
            - link: "#features"
              text: "Features"


            # button loop
            - link: "https://docs.groupdocs.cloud/signature/release-notes/"
              text: "Release Notes"

            # button loop
            - link: "https://purchase.groupdocs.cloud/pricing"
              text: "Pricing"

    right:
        link_download: "https://github.com/groupdocs-signature-cloud/groupdocs-signature-cloud-java"
        link_learn: "https://docs.groupdocs.cloud/signature/"
        link_buy: "https://purchase.groupdocs.cloud/buy"

############################# Overview ############################
overview:
    enable: true
    content: |
      Use Java SDK for GroupDocs.Signature Cloud to get started with our e-signature API. It is a wrapper around GroupDocs.Signature REST APIs, that allows you to work with GroupDocs.Signature Cloud in Java quickly and easily, gaining all benefits of strong types and IDE highlights. The distribution is available at GitHub. The repository includes working examples, to get you started in no time.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          An overview of the features supported by GroupDocs.Signature Cloud.
      
        left:
          enable: true
          icon: "fas fa-cogs"
          title: "Signature Options"
          content: |
            * Text
            * Image
            * Digital
            * Barcode
            * QR-Code            
        right:
          enable: true
          icon: "fas fa-crop"
          title: "Retrieve"
          content: |
            * Document Pages information
            * Document Properties
            * Text and Digital
            * Barcode and QR-Code
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Signature Cloud supports electronically signing a number of document formats.

        left:
          enable: true
          table:
            # table loop
            - title: "Supported Formats"
              content: |
                * **Word Processing**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, ODT, OTT, RTF, TXT
                * **Spreadsheet**: XLS, XLSX, XLSB, XLSM, ODS, OTS, CSV, TSV
                * **Presentation**: PPT, PPTX, PPTM, PPS, PPSX, PPSM, POTX, POTM, ODP, OTP

        right:
          enable: true
          table:
            # table loop
            - title: "Image and Other Formats"
              content: |
                * **Image**: BMP, DjVu, DNG, EMF, EPS, GIF, JP2, JPF, JPX, J2C, J2K, JPM, JPG, JPEG, ODG, PNG, PS, PSD, SVG, TIF, TIFF, WebP, WMF
                * **Portable**: PDF


      ## TAB THREE ##
      tab_three:
        description: |
          Supported Operating Systems and Frameworks
      
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operating Systems"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Supported Frameworks"
              content: |
                * Java 7 (1.7) and above

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Development Environments"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Build Automation Tool"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "Advanced Document Signature REST API Features"

    feature:
      # feature loop
      - icon: "fas fa-list-alt"
        content: "Provide the list of supported document formats"

      # feature loop
      - icon: "fas fa-file"
        content: "Retrieve document pages information"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Retrieve document properties"
      
      # feature loop
      - icon: "fas fa-check"
        content: "Verify Text and Digital signatures"

      # feature loop
      - icon: "fas fa-barcode"
        content: "Verify Barcode and QR-Code signatures"

      # feature loop
      - icon: "fas fa-retweet"
        content: "Cross-Platform Compatibility"
      # feature loop
      - icon: "fas fa-search"
        content: "Search multiple signatures"
      
      # feature loop
      - icon: "fas fa-sign-in-alt"
        content: "Add multiple signatures"
    
    more_feature:
      # more_feature_loop
      - title: "Get Started with Cloud Signature REST API"
        content: "It is easy to get started with GroupDocs.Signature Cloud as there is nothing to install. Simply create an account at GroupDocs Cloud and get your application information. Once you have the App SID & key, you are ready to give the GroupDocs.Signature Cloud REST API a try with any language - on any platform. To help the developers to speed up the development of their projects, we have built SDK for Java, which helps them to integrate the e-signing REST API in their Java apps without worrying about the low-level details of handling the HTTP requests and responses."
      # more_feature_loop
      - title: "Supported Signature Types"
        content: "Our e-Signature RESTful API supports the following signature types:"
        content: |
                * Text Signature
                * Image Signature
                * Barcode Signature
                * QR-Code Signature
                * Digital Signature
                * Stamp Signature
      # more_feature_loop
      - title: "Cloud based e-Signing API Features"
        content: "Using the GroupDocs.Signature Cloud SDK for Java, the following operations supported by the API with documents can be carried out:"
        content: |
          * Provide list of supported document formats
          * Obtain list of supported Barcode and QR-Code encode type names
          * Retrieve document properties like document size, creation and update dates, count of pages etc
          * Retrieve document pages information like pages count etc
          * Support signature for PDF documents
          * Support signature on Microsoft Documents formats like MSWord Documents, Excel Spreadsheets, PowerPoint Presentations
          * Support signature for Open Document Formats, HTML and many more
          * Verify documents for signatures
      # more_feature_loop
      - title: "Security and Authentication"
        content: "The GroupDocs.Storage Cloud SDK for Java as well as the actual API are secured and require authentication. Users need to register at GroupDocs Cloud and get their app access key ID and app secret access key. Authenticated requests require a signature and AppSID query parameters or OAuth 2.0 athrorization header."
      # more_feature_loop
      - title: "Easy to Customize"
        content: "GroupDocs.Signature Cloud SDK is 100% tested and out of the box running. The SDK is open source and has an MIT license. It is highly flexible, so you can use it, and even customize it to suit your needs for absolutely free of charge."
############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Signature Cloud also offers individual SDKs for other popular languages as listed below:"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Signature Cloud for cURL"
          image: "/sdk/272x272/groupdocs_signature-for-curl.webp"
          product: "GroupDocs.Signature"
          platform: "cURL"
          link: "/signature/curl/"

        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for .NET"
          image: "/sdk/272x272/groupdocs_signature-for-net.webp"
          product: "GroupDocs.Signature"
          platform: ".NET"
          link: "/signature/net/"

        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for PHP"
          image: "/sdk/272x272/groupdocs_signature-for-php.webp"
          product: "GroupDocs.Signature"
          platform: "PHP"
          link: "/signature/php/"

        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for Python"
          image: "/sdk/272x272/groupdocs_signature-for-python.webp"
          product: "GroupDocs.Signature"
          platform: "Python"
          link: "/signature/python/"

        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for Ruby"
          image: "/sdk/272x272/groupdocs_signature-for-ruby.webp"
          product: "GroupDocs.Signature"
          platform: "Ruby"
          link: "/signature/ruby/"

        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for Node.js"
          image: "/sdk/272x272/groupdocs_signature-for-node.webp"
          product: "GroupDocs.Signature"
          platform: "Node.js"
          link: "/signature/nodejs/"
        # solution loop
        - img_alt: "GroupDocs.Signature Cloud SDK for Android"
          image: "/sdk/272x272/groupdocs_signature-for-android.webp"
          product: "GroupDocs.Signature"
          platform: "Android"
          link: "/signature/android/"
        

############################# Back to top ###############################
back_to_top:
  enable: true
---