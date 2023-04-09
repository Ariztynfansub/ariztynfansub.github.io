---
title: "Encode Anime X265 10bit bằng phần mềm HandBrake"
date: 2023-04-09T10:00:00+07:00
slug: "encode-anime-x265-10bit-with-handbrake"
image: encode-anime-x265-10bit-with-handbrake.webp
categories: Guide
tags: ['Làm subtitle','HandBrake','Encode']
lastmod: '2023-04-09T13:13:30+07:00'
---
## Đôi lời
Encode thường là bước cuối cùng để đưa ra sản phẩm. Mục đích Encode sẽ giúp giảm dung lượng sản phẩm đầu ra, đổi định dạng âm thanh cũng như ghép subtitle vào sản phẩm luôn ở dạng Hardsub. Ở bài viết này mình sẽ chỉ chia sẻ cài đặt thông số mà mình dùng để encode. Nên tuỳ vào cảm nhân mà bạn có thể tự lựa chọn cài đặt của riêng mình không cần phải giống mình đâu.   
Encode rất ngốn tài nguyên máy tính nên nếu encode thì hãy tắt các chương trình đang chạy khác để tăng tốc độ encode.   
## Các thứ cần chuẩn bị
### File video   
Hãy đảm bảo file video không bị lỗi và có chất lượng cao nhất có thể. Mình thường sử dụng video định dạng .mkv hoặc là .mp4
### HandBrake   
Tải HandBrake phù hợp với hệ điều hành của bạn tại đây: [Download](https://handbrake.fr/downloads.php)   
Đối với Windows thì tải về xong bạn sẽ được một file .exe. Mở nó lên để cài vào máy, bạn có chọn nơi lưu ở đâu cũng được nhưng để hiệu năng tốt nhất thì nên cài ở ổ SSD.   
## Các bước thực hiện   
### Mở HandBrake và chọn video cần encode    
Sau khi mở HandBrake thì cửa sổ như hình dưới sẽ hiện lên.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-1.webp" loading="lazy" title="Giao diện của HandBrake sau khi mở lên." alt="Giao diện của HandBrake sau khi mở lên.">
		<figcaption>Giao diện của HandBrake sau khi mở lên.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Giờ thì tiến hành mở file video cần encode. Có thể kéo thả file video vào hoặc bấm mục File Open a single video file. như trên ảnh rồi chọn file mình cần.
### Cài đặt thông số để encode x265 10bit   
#### Tab Summary
Sau khi mở file video thì cửa sổ sẽ có giao diện như hình dưới.
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-2.webp" loading="lazy" title="Giao diện của HandBrake sau khi mở file video." alt="Giao diện của HandBrake sau khi mở file video.">
		<figcaption>Giao diện của HandBrake sau khi mở file video.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Bấm chọn tại mục **Format** rồi chọn **mkv** (để sau khi encode thì file sẽ ra dạng .mkv như vầy sẽ dễ thêm phụ để, font,… sau này hơn) hoặc nếu thích file .mp4 thì cứ để nguyên đó.
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-3.webp" loading="lazy" title="Chọn MKV từ format." alt="Chọn MKV từ format.">
		<figcaption>Chọn MKV từ format.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
#### Tab Demension   
Tiếp theo bấm vào tab Dimension như hình dưới. Rồi chọn Custom.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-4.webp" loading="lazy" title="Chọn Custom từ Cropping." alt="Chọn Custom từ Cropping.">
		<figcaption>Chọn Custom từ Cropping.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
#### Tab Video   
Bấm qua tab Video và chọn như hình dưới.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-5.webp" loading="lazy" title="Chọn H.265 10-Bit (x265)." alt="Chọn H.265 10-Bit (x265).">
		<figcaption>Chọn H.265 10-Bit (x265).</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
**Chọn tiếp (FPS)** rồi chọn **Same as source** và check chọn **Constant Framerate** như hình.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-6.webp" loading="lazy" title="Chọn FPS là Same as Source và check chọn Constant Framerate." alt="Chọn FPS là Same as Source và check chọn Constant Framerate.">
		<figcaption>Chọn FPS là Same as Source và check chọn Constant Framerate.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Tiếp theo tại mục **Quality** của tab Video kéo con dấu về mức 21 (số này càng thấp thì chất lượng file đầu ra càng cao nhưng dung lượng sẽ lớn)   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-7.webp" loading="lazy" title="Kéo con dấu về mức 21." alt="Kéo con dấu về mức 21.">
		<figcaption>Kéo con dấu về mức 21.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Tại mục **Encoder Preset** thì kéo con lăng qua mức **Slow**.   
Tại mục **Encoder Tune** cùng trong tab Video thì chọn theo quy tắc sau:   
- Anime xưa -> chọn **Grain** (video sẽ có hiệu ứng hạt giống anime xưa)   
- Anime hiện đại -> chọn **Animation**.   
Ở đây mình sẽ chọn **Grain** để làm ví dụ. Sau khi chọn xong ta sẽ có hình giống như dưới.
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-8.webp" loading="lazy" title="Chọn Encoder Preset và Encoder Tune." alt="Chọn Encoder Preset và Encoder Tune.">
		<figcaption>Chọn Encoder Preset và Encoder Tune.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
#### Tab Audio   
Bấm qua tab Audio. Thường nếu **không muốn thay đổi âm thanh của video gốc** thì cứ chọn **AAC Passthrough** như hình dưới.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-9.0.webp" loading="lazy" title="Nếu không muốn thay đổi âm thanh của video gốc thì chọn AAC Passthrough." alt="Nếu không muốn thay đổi âm thanh của video gốc thì chọn AAC Passthrough.">
		<figcaption>Nếu không muốn thay đổi âm thanh của video gốc thì chọn AAC Passthrough.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Còn nếu bạn thích FLAC hay Opus thì tại Samplerate chọn 48 như hình dưới để có chất lượng âm thanh tốt nhất (do mình lười tính ba cái này).
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-9.webp" loading="lazy" title="Nếu chọn FLAC hay Opus thì tại Samplerate chọn 48." alt="Nếu chọn FLAC hay Opus thì tại Samplerate chọn 48.">
		<figcaption>Nếu chọn FLAC hay Opus thì tại Samplerate chọn 48.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
#### Tab Subtitle   
Bấm qua tab Subtitle rồi **bỏ check toàn bộ** như hình dưới (do mình sẽ thêm sub bằng MKVToolnix nên không cần thêm sub trong công đoạn này).
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-10.webp" loading="lazy" title="Bỏ chọn tất cả Forced Only và Burn in, Default." alt="Bỏ chọn tất cả Forced Only và Burn in, Default.">
		<figcaption>Bỏ chọn tất cả Forced Only và Burn in, Default.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
> Lưu ý: để thêm subtitle vào bản encode thì yêu cầu file video gốc phải có subtitle kèm theo nó sẵn.   
##### Thêm Subtitle   
Nếu bạn file video gốc đã có subtitle sẵn và bạn muốn bản encode xuất ra cũng có nó thì đầu tiên bấm **Foreign Audio Scan** như hình trên **chọn tiếp subtitle bạn muốn**. Rồi **check chọn các mục dưới đây theo nhu cầu**:
- **Forced Only:** mặc định cho subtitles sẽ tự động phát khi mở video   
- **Burn In:** Subtitle sẽ đè thẳng vào file video luôn nên không thể tắt được => tóm lại là Hardsub. Nếu bạn muốn để upload xem online cắm TV thì có thể chọn.   
- **Default:** cài mặc định phát cho phụ đề khi mở video lên, nếu phần mềm có hỗ trợ phát phụ đề.  
#### Chọn nơi lưu file được encode và tiến hành encode   
Trước khi encode hãy đổi tên file sẽ xuất ra và chọn nơi lưu cho file sau khi encode để không lẫn lộn với file gốc. Rồi bấm **Start Encode** để bắt đầu việc Encode.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-11.webp" loading="lazy" title="Sửa tên file sẽ xuất ra + chọn nơi lưu rồi bấm Start Encode để bắt đầu." alt="Sửa tên file sẽ xuất ra + chọn nơi lưu rồi bấm Start Encode để bắt đầu.">
		<img src="/handbrake-12.webp" loading="lazy" title="Sửa tên file sẽ xuất ra + chọn nơi lưu rồi bấm Start Encode để bắt đầu." alt="Sửa tên file sẽ xuất ra + chọn nơi lưu rồi bấm Start Encode để bắt đầu.">
		<figcaption>Sửa tên file sẽ xuất ra + chọn nơi lưu rồi bấm Start Encode để bắt đầu.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
### Vài tip hỗ trợ encode
> Do quá trình Encode khá lâu nên để nó chạy nhanh nhất có thể hãy tắt hết tất cả chương trình khác trên máy tính(Google Chrome, giả lập Android, File Explorer,...).   
> Với nếu muốn tự động tắt máy tính sau khi encode thì chọn như hình dưới. Lưu ý nhớ tắt hoặc lưu các chương trình khác lại rồi mới làm việc này nhá!

{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/handbrake-13.webp" loading="lazy" title="Chọn Shutdown để máy tự động tắt sau khi encode." alt="Chọn Shutdown để máy tự động tắt sau khi encode.">
		<figcaption>Chọn Shutdown để máy tự động tắt sau khi encode.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 

>> Cảm ơn bạn đã đọc bài viết của mình! Nếu có thắc mắc đừng ngần ngại bình luận ở dưới.
