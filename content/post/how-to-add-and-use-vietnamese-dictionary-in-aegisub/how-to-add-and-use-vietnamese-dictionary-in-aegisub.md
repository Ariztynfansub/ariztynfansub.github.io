---
title: "Cách cài và dùng (cơ bản) bộ kiểm tra lỗi chính tả tiếng Việt trong Aegisub"
date: 2023-05-14T16:23:36+07:00
description: Hướng dẫn cài từ điển tiếng Việt và xài để check lỗi chính tả trong Aegisub
image: cover-how-to-add-and-use-vietnamese-dictionary-in-aegisub.webp
categories: Guide
tags: ['Làm subtitle','Aegisub']
---
## Đôi lời  
Trước giờ do xài google ngu nên thành ra lỗi chính tả nhiều quá, nên hôm nay mới tìm được cái này để check chính tả cho Aegisub. Bài viết sẽ hướng dẫn cách cài bộ từ điển tiếng Việt cũng như cách xài nó để check chính tả trong Aegisub.  
> Lưu ý: bộ check chính tả này có một nhược điểm là chỉ check chính ta riêng từng từ một nên không thể check chỉnh tả của một cụm từ được.  
## Các bước cài bộ từ điển tiếng Việt vào Aegisub   
## Tải bộ từ điển tiếng Việt  
[Download](https://github.com/1ec5/hunspell-vi/archive/refs/heads/master.zip).
## Tiến hành cài bộ từ điển tiếng Việt cho Aegisub  
Sau khi tải về và giải nén ra sẽ được một thư mục như sau:
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/thu-muc-sau-khi-duoc-giai-nen-1.webp" loading="lazy" title="Thư mục sau khi được giải nén." alt="Thư mục sau khi được giải nén.">
		<figcaption>Thư mục sau khi được giải nén.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Mở thụ mục đó -> rồi mở tiếp thự mục **dictionaries** như hình dưới.  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/mo-thu-muc-dictionaries.webp" loading="lazy" title="Mở thư mục dictionaries." alt="Mở thư mục dictionaries.">
		<figcaption>Mở thư mục dictionaries.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Từ trong thư mục **dictionaries** tiến hành copy 2 file:
- vi-DauMoi.aff
- vi-DauMoi.dic 

{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/copy-2-file-vi-DauMoi.aff-va-vi-DauMoi.dic.webp" loading="lazy" title="Copy 2 file vi-DauMoi.aff + vi-DauMoi.dic." alt="Copy 2 file vi-DauMoi.aff + vi-DauMoi.dic.">
		<figcaption>Copy 2 file vi-DauMoi.aff + vi-DauMoi.dic.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Bây giờ ta sẽ đi tới thư mục cài Aegisub trên máy. Nếu bạn xài windows thì thường nó sẽ nằm ở ổ C.
Máy mình lưu Aegisub ổ D nên mình sẽ mở nó ở ổ D. Và khi mở thư mục cài Aegisub thì ta sẽ được hình sau:  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/thu-muc-aegisub.webp" loading="lazy" title="Thư mục Aegisub." alt="Thư mục Aegisub.">
		<figcaption>Thư mục Aegisub.</figcaption>	
	</figure>
</p>
{{< /raw_html >}}  
Tiếp tục mở thư mục **dictionaries**.  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/thu-muc-dictionaries-cua-thu-muc-cai-aegisub.webp" loading="lazy" title="Mở thư mục dictionaries của thư mục cài Aegisub." alt="Mở thư mục dictionaries của thư mục cài Aegisub.">
		<figcaption>Mở thư mục dictionaries của thư mục cài Aegisub.</figcaption>	
	</figure>
</p>{{< /raw_html >}} 
Rồi chuột phải trong thư mục chọn **Paste** hoặc dùng ấn **Ctrl+V**. Ta sẽ được như hình sau:  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/sau-khi-paste-vao-thu-muc-dictionaries-cua-thu-muc-cai-aegisub.webp" loading="lazy" title="Sau khi paste vào thư mục dictionaries của thư mục cài Aegisub." alt="Sau khi paste vào thư mục dictionaries của thư mục cài Aegisub.">
		<figcaption>Sau khi paste vào thư mục dictionaries của thư mục cài Aegisub.</figcaption>	
	</figure>
</p>{{< /raw_html >}}  
Tiếp tục click chuột phải và copy file **vi-DauMoi.dic**.
Sau đó đi đến thư mục theo đường link sau (mình xài win nên không biết trên Mac thì sẽ thế nào nên các bạn tự mò nhé):  
> Lưu ý: Tuỳ theo tên User của máy tính bạn là gì mày thay đổi chỗ [] thành tên phù hợp. Với nhớ check cho phép hiển thị các folder ẩn trong máy tính để truy cập thư mục này.  

Link thư mục: **C:\Users\[]\AppData\Roaming\Aegisub\dictionaries**  
Vào được trong đây rồi thì ấn chuột phải trong thư mục và chọn **Paste** hoặc dùng ấn **Ctrl+V**.  
Làm xong ta sẽ có hình như sau:  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/sau-khi-paste-vao-thu-muc-dictionaries-cua-thu-muc-aegisub-trong-roaming.webp" loading="lazy" title="Sau khi paste vào thư mục dictionaries của thư mục Aegisub trong roaming." alt="Sau khi paste vào thư mục dictionaries của thư mục Aegisub trong roaming.">
		<figcaption>Sau khi paste vào thư mục dictionaries của thư mục Aegisub trong roaming.</figcaption>	
	</figure>
</p>{{< /raw_html >}}  
Việc cài đặt đã xong, giờ chỉ cần khởi động lại Aegisub là có thể xài bộ từ điển tiếng Việt để check chính tả rồi.  
## Cách xài bộ từ điển tiếng Việt trong Aegisub để check chính tả  
Đầu tiên ta sẽ cần một file sub bất kỳ nào đó bạn muốn check chính tả.
Sau khi mở file sub lên với Aegisub thì hãy bấm vào **Subtitle** ở gốc trên gần bên trái của cửa sổ Aegisub rồi bấm tiếp **Spell Checker...** từ danh sách trượt xuống như hình dưới.
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/mo-spell-checker-trong-aegisub.webp" loading="lazy" title="Mở Spell Checker... trong Aegisub." alt="Mở Spell Checker... trong Aegisub.">
		<figcaption>Mở Spell Checker... trong Aegisub.</figcaption>	
	</figure>
</p>{{< /raw_html >}}  
Sau đó một cửa sổ nhỏ sẽ hiện lên. Tiếp tục chọn **English (U.S.)** rồi chọn **vi-DauMoi** (Đây là từ điển tiếng Việt mà ta đã cài) như hình sau:  
{{< raw_html >}}  
<p align="center">
	<figure>
		<img src="/chon-vi-DauMoi.webp" loading="lazy" title="Chọn vi-DauMoi." alt="Chọn vi-DauMoi.">
		<figcaption>Chọn vi-DauMoi.</figcaption>	
	</figure>
</p>{{< /raw_html >}}  
Sau đó cũng tại cửa đó Aegisub sẽ tự động chuyển chúng ta đến các line chứa từ mà bộ từ điển tiếng Việt đang nghi vấn là bị sai chính tả.
Bây giờ mình sẽ giải thích các nút bấm trên cửa sổ này nhìn ảnh trên để tiện so sánh:
- `Replace`: thay từ hiện tại đang nghi vấn là sai chính tả - **Misspelled word:** bằng từ trong ô **Replace with:** (ô này có thể edit thành từ bạn muốn).
- `Replace All`: tương tự cái trên nhưng phạm vi thay thế sẽ áp dụng cho toàn bộ file sub (nên lưu ý khi sử dụng).  
- `Ignore`: bỏ qua từ đang bị nghi vấn bị sai chính tả (bấm cái này nếu thấy từ trong ô **Misspelled word:** đúng chính tả sẵn rồi).  
- `Ignore All`: tương tự cái trên nhưng áp dụng cho toàn bộ file sub => nó sẽ bỏ qua toàn bộ các từ giống trong ô **Misspelled word:**.
- `Add to dictionary`: thêm từ ở ô **Misspelled word:** vào từ điện để sau này từ đó sẽ không bị xem là sai chính tả nữa.  
- `Remove from dictionary`: Xoá từ trong ô **Replace with:** khỏi từ điển (chỉ có thể dùng khi nó có trong file từ điển). **Lưu ý: là chức năng này chỉ có thể xoá những từ được thêm bằng Add to dictionary mà thôi."  

Sau khi nắm hết các chức năng đó rồi thì bạn chỉ việc chọn các chức năng đó trên cửa sổ Spell Checker cho tới nó chạy hết các line trong file sub và hiện thông báo "... script gì gì đó" là xong chúc mừng bạn đã check lỗi chính tả hết file sub của mình rồi.  
> Cảm ơn các bạn đã đọc bài viết của mình! 🙂
