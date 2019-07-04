## REST TESTING là gì?

# RESTful API là gì?
<p>1. REST viết tắt cho "Representational State Transfer". Là một kiểu kiến trúc phần mềm hoạt động dựa trên phương thức truyền tải phi trạng thái, phổ biết nhất là HTTP.</p>)
  /Pở đây, truyền tải phi trạng thái: stateless communications protocol là gì?: Trong lập trình web, chúng ta có sự tương tác giữa client với server. Phần mềm gồm 2 thành phần chính: phần mềm và data. Như vậy, một phần mềm được thiết kế theo tương tác client – server thì phần nhiều tập lệnh sẽ nằm phía server. Client có nhiệm vụ gửi dữ liệu lên để xử lý sau đó nhận kết quả trả về. Vậy stateful vs stateless là gì?

  Stateless là thiết kế không lưu dữ liệu của client trên server. Có nghĩa là sau khi client gửi dữ liệu lên server, server thực thi xong, trả kết quả thì “quan hệ” giữa client và server bị “cắt đứt” – server không lưu bất cứ dữ liệu gì của client. Như vậy, khái niệm “trạng thái” ở đây được hiểu là dữ liệu.</p>)
/p2. Dữ liệu ở REST API thường là XML, YAML,.. bất cứ dạng nào mà máy có thể đọc được, và tiêu biểu được sử dụng nhiều nhất là JSON.</p> 
/p3. Những request cơ bản của REST:
GET Đọc/lấy dữ liệu

POST Thêm mới dữ liệu

PUT Cập nhật dữ liệu đang tồn tại

DELETE xóa bỏ dữ liệu</p>)
