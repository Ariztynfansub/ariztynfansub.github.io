---
title: "Chuyển đổi định dạng từ Vob Subtitle sang Srt Subtitle"
date: 2023-04-04T22:20:57+07:00
slug: "convert-vob-subtitle-to-srt"
image: convert-vob-subtitle-to-srt.webp
categories: Guide
tags: ['Làm subtitle','VSRip','Subtitle Edit','UltraISO']
---
## Đôi lời   
Do mình toàn dịch mấy bộ anime cũ nên sẽ luôn gặp mấy file DVD, mà tính mình thì nhanh quên nên mới có bài viết này. Và như tiêu đề, thì để dịch được thì cần tách Vob subtitle từ DVD rồi chuyển đổi về dạng Srt subtitle để dễ edit với Aegisub. Mình nghĩ trên mạng sẽ có nhiều cách khác tiện hơn, nên nếu mấy bạn biết thì có thể bình luận mách mình nhé 😊.   
## Các thứ cần chuẩn bị   
### Thư mục DVD   
Thường khi tải DVD trên internet thì thứ các bạn tải về thường là một file có đuôi **.iso** hoặc là nguyên một danh sách các file tùm lum các file có đuôi như:
- **.BUF**
- **.IFO**
- **.chunks**
- **.**
### Phần mềm   
#### UltraISO (nếu file dvd có định dạng .iso)    
Không bắt buộc phải là UltraISO, miễn là bạn có phần mềm để mount các file **.iso** vào ổ CD Drive trên máy tính, để đọc/sao chép dữ liệu bên trong là được.   
[Link tải UltraISO & hướng dẫn cài đặt.](https://kienthucphanmem.com/phan-mem/ultraiso-premium/)    
#### VSRip
Mình không xài win 11 nên không biết nó có chạy được trên đó không. Nhưng win 10 thì vô tư. Phần mềm này sẽ giúp ta lấy file Vob subtitle từ DVD ra.   
[Link tải VSRip](https://sourceforge.net/projects/guliverkli/files/VSRip/VSRip%201.0.0.6/)   
##### Hướng dẫn tải & cài đặt VSRip   
Sau khi vào link trên. Bấm **VSRip_20030530.zip** thì web sẽ reload lại, bạn chỉ việc đợi nó load xong là tự động file .zip sẽ được tải xuống và yêu cầu bạn chọn nơi lưu.   
Cứ giải nén file **VSRip.exe** trong file **VSRip_20030530.zip** ra mở lên là phần mềm sẽ tự động chạy không phải cài đặt.
#### Subtitle Edit   
Phần mềm phụ trách chuyển đổi Vob subtitle sang Srt subtitle.   
[Link tải Subtitle Edit](https://www.nikse.dk/subtitleedit)   
##### Hướng dẫn tải & cài đặt Subtitle Edit   
Sau khi bấm link tải thì bấm vào vùng khoanh đỏ như trên hình.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/download-subtitle-edit-1.webp" loading="lazy" title="Tải bản Subtitle Edit bản mới nhất." alt="Tải bản Subtitle Edit bản mới nhất.">
		<figcaption>Tải bản Subtitle Edit bản mới nhất.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Nỏ sẽ mở ra tab mới trên trình duyệt. Nếu bạn là Windows thì bấm chọn mục khoanh đỏ trên hình. Có nếu hệ điều hành của các bạn khác thì chịu khó đọc để kiếm.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/download-subtitle-edit-2.webp" loading="lazy" title="Tải bản Subtitle Edit cho Windows." alt="Tải bản Subtitle Edit cho Windows.">
		<figcaption>Tải bản Subtitle Edit cho Windows.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Giải nén file .zip vừa tải về và chạy file .exe chọn nơi lưu tạo shortcut các kiểu là xong.   
## Các bước   
### Nếu file có dịnh dạng là .iso (bỏ qua bước này nếu không phải .iso)    
Mở thư mục chứa file .iso. **Click chuột phải** vào nó. **Chọn mount** như hình dưới.   
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/right-click-iso-file-select-mount.webp" loading="lazy" title="Click chuột phải vào file .iso chọn mount." alt="Click chuột phải vào file .iso chọn mount.">
		<figcaption>Click chuột phải vào file .iso chọn mount.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}   
xong rồi thì bấm vào **This PC** bạn sẽ thấy như hình dưới đây.
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/mounted.webp" loading="lazy" title="Sau khi mount file .iso thành công." alt="Sau khi mount file .iso thành công.">
		<figcaption>Sau khi mount file .iso thành công.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
Nhấp đúp mở ổ DVD Drive ta được hình như sau.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/open-dvd-drive-1.webp" loading="lazy" title="Mở ổ đĩa dvd drive." alt="Mở ổ đĩa dvd drive.">
		<figcaption>Mở ổ đĩa dvd drive.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}   
Tiếp tục mở thư mục **VIDEO_TS** ta được như hình dưới.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/open-dvd-drive-2.webp" loading="lazy" title="Mở thư mục VIDEO_TS." alt="Mở thư mục VIDEO_TS.">
		<figcaption>Mở thư mục VIDEO_TS.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}   
> Nếu DVD tải gồm tập hợp các file có đuôi giống với các file trên hình thì coi như đã sẵn sàng sang bước tiếp theo.   
### Tách lấy Vob subtitle   
Mở file **VSRip.exe** lên. Chọn **Load IFO** như hình dưới.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/vsrip-open.webp" loading="lazy" title="Mở VSRip và chọn Load IFO." alt="Mở VSRip và chọn Load IFO.">
		<figcaption>Mở VSRip và chọn Load IFO.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Mở đến nơi chứa các file DVD (chứa các file .IFO). Nếu DVD là file .iso thì đến ổ DVD Drive như đã làm ở bước 3.1 của mục lục. Dưới đây là ảnh giao diện của VSRip khi dò thư mục để mở file .IFO.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-1.webp" loading="lazy" title="Mở vị trí file.IFO trên VSRip." alt="Mở vị trí file.IFO trên VSRip.">
		<figcaption>Mở vị trí file.IFO trên VSRip.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Có rất nhiều File .IFO để chọn vậy file nào mới là đúng? Để biết thì ta quay lại window explorer của thư mục DVD. Tại thư mục bấm **Size** gốc như hình để lọc các file theo kích thước giảm dần như hình.
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-2.webp" loading="lazy" title="Lọc các file trong thư mục chứa các file của DVD theo Size giảm dần." alt="Lọc các file trong thư mục chứa các file của DVD theo Size giảm dần.">
		<figcaption>Lọc các file trong thư mục chứa các file của DVD theo Size giảm dần.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Sau khi làm vậy ta sẽ thấy ba file có dung lượng lớn nhất là:
- VTS_02_1.VOB   
- VTS_03_1.VOB   
- VTS_04_1.VOB   

Chúng chính là các file phim. Vậy thì **quay lại cửa sổ VSRip** hãy **chọn các file .IFO có tên giống với các file phim** trên là:
- VTS_02_0.IFO   
- VTS_03_0.IFO   
- VTS_04_0.IFO   

{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-3.webp" loading="lazy" title="Các file .IFO mà ta sẽ dùng để chuyển đổi sang .srt." alt="Các file .IFO mà ta sẽ dùng để chuyển đổi sang .srt.">
		<figcaption>Các file .IFO mà ta sẽ dùng để chuyển đổi sang .srt.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
Đây là các file chứa Vob subtitle. Giờ mình sẽ ví dụ tiến hành lấy subtitle của file **VTS_02_0.IFO**, 2 file còn lại cứ làm tương tự.
Sau khi chọn file **VTS_02_0.IFO** và bấm **Open** từ cửa sổ VSRip như hình dưới.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-4.webp" loading="lazy" title="Chọn file VTS_02_0.IFO và bấm Open." alt="Chọn file VTS_02_0.IFO và bấm Open.">
		<figcaption>Chọn file VTS_02_0.IFO và bấm Open.</figcaption>	
	</figure>
</p>
<p align="center">
	<figure>
		<img src="/VSRip-5.webp" loading="lazy" title="Chọn nơi lưu file Vob subtitle sau khi xuất ra." alt="Chọn nơi lưu file Vob subtitle sau khi xuất ra.">
		<figcaption>Chọn nơi lưu file Vob subtitle sau khi xuất ra.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
Bấm tiếp **Save to...** để chọn nơi lưu file Vob subtitle sau khi xuất ra. Như hình trên thì mình đang lưu ở thư mục New Folder ở Desktop.   
Xong tiếp tục click **Next >** từ hình trên. Tại trang tiếp theo ta sẽ click vào English như hình dưới để bỏ chọn Japanese vì thứ ta cần lấy là English Subtitle.   
> Lưu ý: nếu không bỏ chọn Japanese thì nguy cơ khi chuyển đổi bằng Subtitle Edit sẽ không convert chính xác English Subtitle mà ta muốn.   

{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-6.webp" loading="lazy" title="Click English(en) để bỏ chọn Japanese(jap)." alt="Click English(en) để bỏ chọn Japanese(jap).">
		<figcaption>Click English(en) để bỏ chọn Japanese(jap).</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
Tiếp tục bấm **Next >** ở hình trên để tiến hành tách.   
Khi **Done!** xuất hiện như hình dưới thì có nghĩa là Vob subtitle đã được tách xong.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-7.webp" loading="lazy" title="Quá trình tách Vob subtitle và màn hình khi quá trình hoàn tất." alt="Quá trình tách Vob subtitle và màn hình khi quá trình hoàn tất.">
		<figcaption>Quá trình tách Vob subtitle và màn hình khi quá trình hoàn tất.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
Mở thư mục Newfolder ở Desktop nơi lưu file subtitle sau khi tách ra thì sẽ có thành quả như sau.
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/VSRip-8.webp" loading="lazy" title="Thành quả sau khi tách là 2 hai file Vob subtitle .idx và .sub." alt="Thành quả sau khi tách là 2 hai file Vob subtitle .idx và .sub.">
		<figcaption>Thành quả sau khi tách là 2 hai file Vob subtitle .idx và .sub.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}
> Tiếp tục lặp lại như vậy với 2 file VTS_03_0.IFO, VTS_04_0.IFO   
### Chuyển đổi Vob subtitle sang Srt subtitle     
Mở Subtitle Edit bằng shortcut từ Desktop. Rồi chọn **Tools** -> **Batch convert...** như hình.
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/subtitle-edit-1.webp" loading="lazy" title="Click 'Tools" rồi click 'Batch convert...'." alt="Click 'Tools" rồi click 'Batch convert...'.">
		<figcaption>Click 'Tools" rồi click 'Batch convert...'.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
Sau đó **cửa sổ Batch convert sẽ hiện ra**.   
Từ cửa số window explorer của Newfolder nơi lưu Vob subtitle, click giữ chuột trái vào file **VTS_02_0.sub** rồi kéo thả vào **cửa sổ Batch convert**, rồi ta sẽ thành quả như hình.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/subtitle-edit-2.webp" loading="lazy" title="Click giữ chuột trái vào file VTS_02_0.sub và kéo thả vào Batch convert." alt="Click giữ chuột trái vào file VTS_02_0.sub và kéo thả vào Batch convert.">
		<img src="/subtitle-edit-3.webp" loading="lazy" title="Click giữ chuột trái vào file VTS_02_0.sub và kéo thả vào Batch convert." alt="Click giữ chuột trái vào file VTS_02_0.sub và kéo thả vào Batch convert.">
		<figcaption>Click giữ chuột trái vào file VTS_02_0.sub và kéo thả vào Batch convert.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 

Chọn nơi lưu file .srt sau khi chuyển đổi và cài đặt thông số như hình dưới rồi bấm **Convert**. Sau đó đợi nó chạy được **100% và đổi thành Converted** trên Status là xong, ta đã có file english subtitle có đuôi .srt rồi.   
{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/subtitle-edit-4.webp" loading="lazy" title="Cài đặt thông số cho file .srt sắp xuất ra." alt="Cài đặt thông số cho file .srt sắp xuất ra.">
		<figcaption>Cài đặt thông số cho file .srt sắp xuất ra.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 

>Lưu ý: quá trình convert diễn ra khá lâu nên hãy đảm bảo bạn làm theo các bước mình chỉ rồi mới bấm **Convert**.    
Mở thư mục Newfolder ở Desktop nơi lưu file .srt mà ta đã chọn để xem thành quả.   

{{< raw_html >}}
<p align="center">
	<figure>
		<img src="/subtitle-edit-5.webp" loading="lazy" title="Thành quả file english subtitle VTS_02_0.srt." alt="Thành quả file english subtitle VTS_02_0.srt.">
		<figcaption>Thành quả file english subtitle VTS_02_0.srt.</figcaption>	
	</figure>
</p>
{{< /raw_html >}} 
>Tiếp tục lặp lại như vậy với 2 file VTS_03_0.sub, VTS_04_0.sub   

>Lưu ý: trong quá trình chuyển đổi sang **.srt** có thể sẽ có vài đoạn subtitle sẽ bị sai do Subtitle Edit không OCR được nên đừng xoá file Vob subtitle vội. Để nhiều khi còn có thể so sánh để tự sửa lỗi.   

