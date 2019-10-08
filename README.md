Ví dụ, Trong trường hợp cửa hàng có 5 bó hoa, và mảng độ thơm tương ứng là (1,−2,1,3,−4) và chủ cửa hàng đưa ra những dãy con gợi ý là (1,−2),(3,−4),(1,3),(1,−2,1,3). Sau đó nếu Hiếu chọn dãy con thứ ba và dãy con thứ bốn thì cách tính độ thơm sẽ dựa vào mảng độ thơm ban đầu như sau:
Bó hoa thứ nhất: 1∗1=1 thêm vào độ thơm, vì bông hoa thuộc bó hoa thứ nhất chỉ xuất hiện ở dãy con thứ tư mà Hiếu đã chọn.
Bó hoa thứ hai : (−2)∗1=−2 đc thêm vào, vì bông hoa thuộc bó hoa thứ hai chỉ xuất hiện ở dãy con thứ tư mà Hiếu đã chọn.
Bó hoa thứ ba: 1∗2=2, vì bông hoa thuộc bó hoa thứ ba xuất hiện ở cả hai dãy con mà Hiếu đã chọn.
Bó hoa thứ tư: 3∗2=6, vì bông hoa thuộc bó hoa thứ tư xuất hiện ở cả hai dãy con mà Hiếu đã chọn.
Bó hoa cuối cùng" (−4)∗0=0 v bông hoa thuộc bó hoa thứ năm không xuất hiện ở cả hai dãy con mà Hiếu đã chọn.
Như vậy, tổng độ thơm sẽ là : 1+(−2)+2+6+0=7. Lưu ý rằng, Hiếu có thể chọn số dãy con bất kì trong các gợi ý. Thậm chí có thể chọn hết các gợi ý hoặc không chọn dãy con nào cả. Các bạn hãy giúp Hiếu có tỉ lệ tỏ tình thành công cao nhất có thể nhé.
Input:
Dòng đầu tiên chứa 2 số n,m(1<=n,m<=100) - Tương ứng là số lượng bó hoa và số lượng dãy con gợi ý bởi chủ cửa hàng.
Dòng thứ hai là n số nguyên a[1],a[2],...a[n] thể hiện độ thơm của từng bó hoa có chỉ số 1,2..,n.(−100<=a[i]<=100)
m dòng tiếp theo, mỗi dòng gồm 2 số nguyên l[i] và r[i] mô tả 2 chỉ số của dãy con mà chủ cửa hàng đã gợi ý. (1<=l[i]<=r[i]<=n). Có nghĩa nó thể hiện dãy con a[l[i]],a[l[i]+1],...a[r[i]]. Mỗi dãy con có thể lặp lại nhiều hơn một lần.
Output:
In số nguyên duy nhất - Độ thơm tối đa mà Hiếu có thể đạt được sau khi xem xét các gợi ý.
Example 01:
Input:
5 4
1 -2 1 3 -4
1 2
4 5
3 4
1 4
Output:
7
