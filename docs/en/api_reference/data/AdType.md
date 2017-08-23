# AdType (enum)
AdType describes the type of ad.<br>In addition, the number of available characters of ad vreatives vary with selected devices.

### Service
+ [AdGroupAdService](../services/AdGroupAdService.md)

| Value | Description | 
|---|---|
| TEXT_LONG_AD1| Text ad is "title is 15 characters" and "description is 19 characters/ 19 characters". <br>It is available for PC, Smartphone and Tablet. (Recommended) |
| TEXT_LONG_AD2| Text ad is "title is 15 characters" and "description is 33 characters". <br>It is available for PC, Smartphone and Tablet.  |
| TEXT_SHORT_AD1| Short text ad is "title is 12 characters" and "description is 12 characters". <br>It is available for Mobile. (Recommended)|
| TEXT_SHORT_AD2| Short text ad is "title is 14 characters" and "description is 19 characters". <br>It is available for Mobile.  |
| POS_AD| Positioning text is "description is 33 characters". |
| APP_AD1|Ad for Mobile App Install. <br>*Currently this ad type is not available for ad creation.|
| RESPONSIVE_AD| Responsive Ad which flexibly adjusts its image size and trimmed to the size of ad place. |
| STATIC_FRAME_AD| Static frame ad which flexibly adjusts to 3 layout types to the size of ad place. 。<br>*More information about the layout is referable on <a href="./AdLayout.md">AdLayout</a>. |
| NONE| Image ad which is displayed on the specified ad place and does not require any text within the ad.  |

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
