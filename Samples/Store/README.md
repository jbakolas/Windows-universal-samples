﻿<!---
  category: AppSettings
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=627610&clcid=0x409
--->

# Store sample

This sample demonstrates how to perform in-app feature or product purchases operations
and use the licensing API provided by the Windows Store
to determine the license status of an app or a feature that is enabled by an in-app purchase.

The Windows Store supports the following types of in-app purchases:

-   Purchasing the app itself.
-   Purchasing a durable in-app product, meaning that after the purchase, the user owns the product until it (optionally) expires.
    For example, a new game level is typically a durable in-app product.
-   Purchasing a consumable in-app product, meaning that the user can purchase it multiple times.
    For example, a game power-up is typically a consumable in-app product.
    The act of confirming that the user received the consumable product is known as "fulfillment".

The sample app demonstrates the following tasks.

-   Check the current license status of an app.
-   Check the expiration date of an app trial period.
-   Check if an in-app product has been purchased through an in-app purchase.
-   Perform an in-app purchase to buy the app.
-   Perform an in-app purchase to buy an in-app product.
-   Check the expiration date (if any) of a product.
-   Confirm the fulfillment of an in-app consumable product.
-   Perform an in-app purchase transaction using the Windows Store commerce platform.
-   Perform an in-app purchase to buy an app feature or product from a large purchase catalog.
-   Launch the Windows Store page for the app, so users can purchase the app or write a review.
-   Generate a receipt that can be used to verify the successful completion of the transaction.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[**Windows.ApplicationModel.Store**](http://msdn.microsoft.com/library/windows/apps/br225197)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:**  Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select **Build** \> **Deploy Solution**. 

### Deploying and running the sample on a Windows 10 Desktop

- To debug the sample and then run it, press F5 or use **Debug** \> **Start Debugging**. To run the sample without debugging, press Ctrl+F5 or use **Debug** \> **Start Without Debugging**.

### Deploying and running the sample on a Windows 10 Phone

- To debug the sample and then run it, press F5 or use **Debug** \> **Start Debugging**. To run the sample without debugging, press Ctrl+F5 or use **Debug** \> **Start Without Debugging**.
