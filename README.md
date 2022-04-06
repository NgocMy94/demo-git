$ git log : giúp bạn xem lại thông tin lịch sự commit, nhằm giám sát sự thay đổi của dự án. Lệnh git log có nhiều tham số để xuất ra, định dạng các thông tin hiện thị theo cách mong muốn. Bạn có thể định dạng cách các thông tin mỗi commit được in ra khi xem, cũng như có thể lọc thông tin nào đó.
$ git show [địa chir nhánh cần thay đổi] : xem lại thông tin cụ thể commit
$ git diff : Kiểm tra sự khác nhau, thay đổi giữa thư mục làm việc và commit cuối, giữa index và commit cuối, giữa các nhánh ... bằng lệnh git diff
$ gitk mở của sổ xem lịch sử commit
Các thuộc ngữ


Working directory là nơi các file mới được tạo, file cũ bị xóa hoặc nơi thực hiện các thay đổi


Staging Area  là khu vực sẽ lưu trữ những thay đổi của bạn trên tập tin để nó có thể được commit, vì muốn   commit tập tin nào thì tập tin đó phải nằm trong Staging Area. Một tập tin khi nằm trong Staging Area sẽ có trạng thái là Stagged


Repository là nơi sẽ ghi lại trạng thái của thư mục và file. Trạng thái được lưu lại đang được chứa như là lịch sử thay đổi của nội dung.


$ git checkout được sử dụng cho hành động chuyển đổi giữa các phiên bản khác nhau của một thực thể nào đó. Lệnh git checkout được sử dụng để chuyển đổi giữa các nhánh trong kho lưu trữ. Hãy cẩn thận với các file khi bạn checkout của bạn và các commit khi chuyển đổi giữa các nhánh.