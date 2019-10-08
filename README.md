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
