# frontend-trainning
front-end là làm xây dựng giao diện từ file thiết kế (cắt file design sang htmp,scc,javascript)hoặc(chuyển file psd,figma,xd sang html)(psd là photoshop)
html là ngôn ngữ đánh dấu siêu văn bản( hypertext markup language)
cấu trúc html gồm:
  <!DOCTYPE html>                (DOCTYPE để khai báo văn bản kiểu html);https://www.w3schools.com/tags/tag_doctype.asp
  html
    head
      title: tiêu đề
      meta charset="utf-8"    (utf-8:bộ mã hóa kí tự Unicode)
      meta name="viewport"    (đáp ứng nội dung co dãn trên các thiết bị có kích thước khác nhau)
      meta name="keywords"    (từ khóa tìm kiếm)
      meta name="Descreption" (mô tả)
      icon
    body

<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>

thuộc tính class dùng khi có kiểu giống nhau, nhiều thằng dùng chung đc 
id là duy nhất 1 id chỉ đc 1 thằng dùng
  
  # gọi id
  . gọi class

########################
ngày 12/10/2020     

  Những thẻ html hay dùng
 Tiêu đề (h1-h6)
 nôi dung( p, span, strong) (strong là thẻ in đậm)
 inline với block
 block: thẻ div, p
 inline: span, thẻ a, strong, img (img là hình ảnh), input (nút để chọn), button(nút bấm)
 img có thuộc tính src (source: đường dẫn đến hình), alt( chữ thay thế cho hình ảnh khi đường dẫn sai)
 thay đổi từ block qua inline và từ inline qua block bằng cách sử dụng thuộc tính display từ css
 thẻ a href =" đường dẫn" targer="_blank"> link test
 
   CSS
 có 3 kiểu inline, internal,external
 inline dùng attribute (thuộc tính) style viết trong thẻ html
 internal dùng thuộc tính style viết trong head
 external viết ở ngoài rồi inport vào bằng thẻ link   <link rel="stylesheet" href="đường dẫn .css">
    thứ tự ưu tiên
      inline
      internal, external( do mình sắp xếp)
 một số thuộc tính thường dùng
    color : red(#ffffff mã hex : lên gg tìm)
    font-family: khai báo font chữ
    font-size: kích cở chữ
    border : viền
    background: màu nền
 ##########
 css box model
 content : nội dung
 padding : khoản cách từ nội dung đề viền
 border : viền
 margin : lề
 top , right , bottom,left
 cú pháp css: 
    selecter gồm id, class,..{property:value; }
    property: thuộc tính 
    value : giá trị
    vd: h1 { color:blue; font-size:12px;}
###############################
  đầu trang css phải có dấu * để chọn all 
  :root    là gốc
  mục đích thường dùng khai báo mã màu
  font-weight : đậm nhạt  ( giống strong)
  font-style: nghiên
  khác nhau giữa display: none và visibility:hidden 
  display mất luôn kích thước nội dung( chiều rộng và cao)
  display-block : chiếm hết diện tích chiều ngang của nội dung
  display-inline : chiếm đủ chiều dộng của nội dung, không lấy hết chiều rộng
  display: flex;  :
  
 
 
 
