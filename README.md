# 128ABC BarcodeVbLib
A Barcode type 128A/B/C library written in Visual Basic .NET, that permit to encode value which you can use with barcode 128.

To use the library simple compile the project with visual studio, copy the generated .dll to your project, get a reference to it and that's all, the code to use it is really simple!

Font can be easily found on internet, like here http://www.jtbarton.com/Barcodes/Code128.aspx where you can find also a good explanation of the difference of each type of encode.


# C# Example
```c#
using BarCodeVbLib;

namespace BarcodeExampleApp
{
    class BarcodeUtils
    {
        // pass the value for which you want to get back the encoded one
        public static string GetBarcodeEncodedValue(string value)
        {
            BarCodeLibClass bclc = new BarCodeLibClass();
            return bclc.Bar128AB(value);
        }
    }
}
```
