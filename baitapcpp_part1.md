## Bài tập if for while

###	1. Viết chương trình nhập vào một số nguyên dương n và in ra màn hình dãy số tự nhiên từ 1 tới n.

```cpp
#include <iostream>
using namespace std; 
 
int main()
{
    int n;
    cout << "Nhap so n: ";
    cin >> n;
    cout << "Tat ca cac so tu 1 den " << n << " la:";
    for (int i = 1; i <= n; i++) {
        cout << " " << i;
    }
    return 0;
}
```


### 2.	Viết chương trình nhập vào một số nguyên n và in ra màn hình các số nguyên chẵn trong khoảng từ 1 tới n.
```cpp
#include <iostream>
using namespace std; 
 
int main()
{
    int n;
    cout << "Nhap so n: ";
    cin >> n;
    cout << "Tat ca cac so chan tu 1 den " << n << " la:";
    for (int i = 1; i <= n; i++) {
        if (i % 2 == 0) {
            cout << " " << i;
        }
    }
    return 0;
}
```
### 3.	Viết chương trình nhập vào số nguyên dương n và in ra màn hình các ước của n.
```cpp
#include <iostream>
using namespace std; 
 
int main()
{
    int n;
    cout << "Nhap so n: ";
    cin >> n;
    cout << "Tat ca cac uoc cua " << n << " la:";
    for (int i = 1; i <= n; i++) {
        if (n % i == 0) {
            cout << " " << i;
        }
    }
    return 0;
}
```
4.	Viết chương trình nhập vào số n và in ra màn hình dãy như sau: 1 3 5......n .... 6 4 2 ( nghĩa là dãy số có các số nguyên dương lẻ nhỏ hơn n nằm bên tay trái còn các số chẵn sẽ nằm bên tay phải.) 
### 5.	Viết chương trình nhập vào số nguyên dương n và in ra màn hình tổng các số chẵn khoảng từ 1 tới n.
```cpp
#include <iostream>
using namespace std; 
 
int main()
{
    int n;
    cout << "Nhap so n: ";
    cin >> n;
    int tong = 0;
    for (int i = 1; i <= n; i++) {
        if (n % 2 == 0) {
            tong = tong + i;
        }
    }
    cout<<"tong cac so chan la: "<<tong<<endl;
    return 0;
}
```
### 6.	Viết chương trình nhập vào 1 số n và in ra màn hình các số nguyên tố trong khoảng từ 1 tới 2n.
```cpp
#include <iostream>

using namespace std;

int main()
{
    int n;
    cout<<"nhap vao n: ";
    cin>>n;

    for(int i = 1; i< 2*n; i++)
    {
        int dem = 0;
        for(int j = 1; j <= i; j++)
        {
            if(i%j==0)
            {
                dem++;
            }
        }
        if(dem == 2)
        {
            cout<<i<<" ";
        }
    }
    return 0;
}
```
7.	Viết chương trình nhập vào 2 số a,b và in ra màn hình các số nguyên tố trong khoảng bị giới hạn bởi a và b (Mọi người lưu ý là a,b nhập ngẫu nhiên nhé!)
8.	Số chính phương là số mà căn bậc hai của nó là 1 số nguyên dương. Viết chương trình nhập vào một số nguyên dương n và cho biết trong khoảng từ 1 tới 2n có bao nhiêu số chính phương. Hãy in ra dãy số chính phương đó.
9.	Viết chương trình tìm ra số lũy thừa 2 đầu tiên lớn hơn 1000.
10.	Viết chương trình nhập vào 1 số n (n>=10) và kiểm tra xem n có phải số nguyên tố hay ko? In kết quả kiểm tra lên màn hình.
### 11.	Viết chương trình nhập vào n và in ra màn hình n!
```cpp
#include <iostream>
using namespace std;

int main()
{
	int n , giaithua = 1;
	cout<<"nhap vao n: ";
	cin >> n;
	for (int i = 1; i <= n; i++) {
		giaithua = giaithua*i;
	}
	cout << giaithua << endl;
    return 0;
}

```
12.	Viết chương trình nhập vào 3 số a,b,c (1<= c <=3). Nếu c=1 in ra tổng a+b, c=2 in ra hiệu a-b, Còn nếu c=3 thì in ra màn hình: " Tớ thích cậu rồi đấy!".
### 13.	Viết chương trình cho nhập 3 số bất kì và kiểm tra xem 3 số đó có thể là 3 cạnh của một tam giác hay không?
```cpp
#include<iostream>
using namespace std;
int main(){
    int a, b, c;
    cout<<"Nhap vao canh a: ";
    cin>>a;
    cout<<"Nhap vao canh b: ";
    cin>>b;
    cout<<"Nhap vao canh c: ";
    cin>>c;
    if( a<b+c && b<a+c && c<a+b ){
        if( a*a==b*b+c*c || b*b==a*a+c*c || c*c== a*a+b*b)
            cout<<"La tam giac vuong";
        else if(a==b==c)
            cout<<"La tam giac deu";
        else if(a==b || a==c || b==c)
            cout<<"La tam giac can";
        else if(a*a > b*b+c*c || b*b > a*a+c*c || c*c > a*a+b*b)    
            cout<<"La tam giac tu";
        else
            cout<<"La tam giac nhon";
    }
    else
        cout<<"Ba canh a, b, c KHONG la ba canh cua mot tam giac";
    return 0;
}
```
### 14.	Viết chương trình nhập vào 2 số nguyên dương a,b tìm và in ra màn hình ước chung lớn nhất của chúng.
```cpp
#include <iostream>
using namespace std;

int main()
{
    int a, b;
    cin >> a >> b;
    int r;
    while (a%b != 0)
    {
        r = a%b;
        a = b;
        b = r;
    }
    cout << "UCLN : "<<b<<endl;
    return 0;
}

```
15.	Viết chương trình nhập vào 2 số nguyên dương a,b tìm và in ra bội chung nhỏ nhất của chúng.

```cpp
#include <iostream>
using namespace std;

int main()
{
    int a, b;
    cin >> a >> b;
    int r;
    int trunggian = a*b;
    while (a%b != 0)
    {
        r = a%b;
        a = b;
        b = r;
    }
    int uoc_chung_lon_nhat = b;
    cout << "BCNN : "<<trunggian/uoc_chung_lon_nhat<<endl;
    return 0;
}

```
