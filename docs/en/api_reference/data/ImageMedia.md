# ImageMedia
The ImageMedia object is a container for storing image.
### Service
+ [MediaService](../services/MediaService.md)

### Inheritance
+ [Media](./Media.md)

| Field | Data Type | Description | 
|---|---|---|
| mediaFileType| enum <a href="./MediaFileType.md">MediaFileType</a>| The file type of image. |
| mediaAdFormat| string| The type of image format.<br>*Image size is described in bracket.<br>・IAB_UAP_LEADER_BOARD（728x90）<br> ・IAB_STANDARD_BANNER（320x50）<br>・IAB_STANDARD_BANNER（640x100）<br>・IAB_UAP_MEDIUM_RECTANGLE（300x250）<br>・IAB_UAP_MEDIUM_RECTANGLE（600x500）<br>・BANNER（468x60）<br>・IAB_UAP_WIDE_SKYSCRAPER（160x600）<br>・YJ_SMART_DOUBLE_BANNER（320x100）<br>・YJ_SMART_DOUBLE_BANNER（640x200）<br>・YJ_1200_628（1200x628）<br>・SQUARE_180（180x180）<br>・SQUARE_300（300x300）<br>・YJ_640_360（640x360） |
| fileSize| xsd:long| The file size of image. |
| width| xsd:long| The width of image. |
| height| xsd:long| The height of image. |
| downloadUrl| xsd:string| The URL for image reference. |
| data| base64Binary| The image file in base64 encode. |

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
