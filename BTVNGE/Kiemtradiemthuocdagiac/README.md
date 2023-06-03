
# **Đề bài: Kiểm tra điểm có nằm trong đa giác hay không ?**
<br>Giả sử bạn là một lập trình viên và đang thiết kế một hệ thống định vị GPS cho một công 
ty vận tải. Bạn muốn kiểm tra xem một vị trí cụ thể có nằm trong vùng đón hàng của 
công ty hay không. Để làm điều này, bạn có thể sử dụng thuật toán kiểm tra một điểm có 
nằm trong hay ngoài một đa giác. Vùng đón hàng có thể được biểu diễn bằng một đa giác 
với các đỉnh tương ứng với các điểm đánh dấu trên bản đồ. Bạn có thể sử dụng các thông 
tin tọa độ để nhập đa giác và điểm cần kiểm tra vào chương trình. Sau đó, chương trình sẽ
trả về kết quả "True" nếu điểm nằm trong vùng đón hàng, hoặc "False" nếu điểm nằm 
ngoài vùng đó. 
<br>
<br>Hãy giải quyết bài toán này trong giới hạn thời gian và không gian sau đây: 
<br>Thời gian: 3 giây 
<br>Bộ nhớ: 50MB
<br>
<br>**Input:**
<br>- Dòng đầu tiên nhập số n là đỉnh của đa giác ( n>2)
<br>- n dòng tiếp theo nhập tọa độ các đỉnh của đa giác 
<br>- Dòng cuối nhập vào tọa độ điểm cần kiểm tra 
<br>**Output:**
<br>- Nếu điểm nằm trong đa giác thì xuất ra kết quả True 
<br>- Nếu điểm nằm ngoài đa giác thì xuất ra kết quả False
<br>
<br>**Ví dụ:** 
<br>    Input 
<br>      3
<br>      2 3 
<br>      5 0 
<br>      4 6
<br>      4 2 
<br>    Output
<br>      True
<br>    Input 
<br>      2
<br>    Output
<br>      Error
