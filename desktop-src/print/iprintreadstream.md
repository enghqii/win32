---
Description: Filters use the IPrintReadStream interface to read data as a raw stream of bytes.
ms.assetid: f31a6547-44ec-4331-8f9b-e46192f4966a
title: IPrintReadStream interface
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# IPrintReadStream interface

Filters use the `IPrintReadStream` interface to read data as a raw stream of bytes.

## Members

The **IPrintReadStream** interface inherits from the [**IUnknown**](https://msdn.microsoft.com/33f1d79a-33fc-4ce5-a372-e08bda378332) interface. **IPrintReadStream** also has these types of members:

-   [Methods](#methods)

### Methods

The **IPrintReadStream** interface has these methods.



| Method                                                            | Description                                                                            |
|:------------------------------------------------------------------|:---------------------------------------------------------------------------------------|
| [**IPrintReadStream::ReadBytes**](iprintreadstream-readbytes.md) | The `ReadBytes` method reads a number of bytes into a buffer.<br/>               |
| [**IPrintReadStream::Seek**](iprintreadstream-seek.md)           | The `Seek` method changes the seek pointer to a new location in the stream.<br/> |



 

## Requirements



|                   |                                                                                                                        |
|-------------------|------------------------------------------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Filterpipeline.h (include Filterpipeline.h)</dt> </dl> |



 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20IPrintReadStream%20interface%20%20RELEASE:%20%285/12/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/en-us/default.aspx. "Send comments about this topic to Microsoft")



