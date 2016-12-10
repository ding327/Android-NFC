## Android-NFC

NFC（Near Field Communication，近场通信）是一种数据传输技术。与Wi-Fi、蓝牙、红外线等数据传输技术的一个主要差异就是有效距离一般不能超过4厘米。但是NFC传输速度要比红外快。目前NFC已经出现了一些应用，例如电子标签识别、刷手机、点对点付款、身份识别、信息记录等.

## Android对NFC的支持

不同的NFC标签之间差异很大，有的只支持简单的读写操作，有时还会采用支持一次性写入的芯片，将NFC标签设计成只读的。当然，也存在一些复杂的NFC标签，例如，有一些NFC标签可以通过硬件加密的方式限制对某一区域的访问。还有一些标签自带操作环境，允许NFC设备与这些标签进行更复杂的交互。这些标签中的数据也会采用不同的格式。但Android SDK API主要支持NFC论坛标准（Forum Standard），这种标准被称为NDEF（NFC Data Exchange Format，NFC数据交换格式）。

## Preview

ScreenShot文件夹为效果演示图（与项目代码无关）

![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot1.png)
![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot2.png)
![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot3.png)
![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot4.png)
![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot5.png)
![](https://raw.githubusercontent.com/smartbetter/Android-NFC/master/ScreenShot/screenshot6.png)

## Usage

直接下载demo查看吧。

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
