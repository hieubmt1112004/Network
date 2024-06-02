![image](https://github.com/hieubmt1112004/Network/assets/125638408/7fc7bcd5-6727-4692-82bf-81798b7c56d4)


Đã đăng kí thành công tài khoản Crytohack



bài intro đầu tiên : 



![image](https://github.com/hieubmt1112004/Network/assets/125638408/4ed77075-f967-4f72-a2f6-7d3f1c0bd334)


Flag có trên đề bài : crypto{y0ur_f1rst_fl4g}




Bài intro thứ 2  



![image](https://github.com/hieubmt1112004/Network/assets/125638408/a2aec09d-ed50-4d23-af4b-432ca371784d)



![image](https://github.com/hieubmt1112004/Network/assets/125638408/d8901db2-dcd9-4c44-80ba-1fe8e583fe9c)



sau khi chạy script đề bài ta thu được flag : crypto{z3n_0f_pyth0n}



Bài intro thứ 3 : 





SYMMETRIC CIPHERS


![image](https://github.com/hieubmt1112004/Network/assets/125638408/a8785b44-e72d-4e12-845b-abae512a96f1)



dựa vào khả năng research ta thu được 1 keywork


![image](https://github.com/hieubmt1112004/Network/assets/125638408/86891d67-f500-40ee-aa3b-46ac2af77ee8)

crypto{Biclique}


Bài tiếp theo : 
![image](https://github.com/hieubmt1112004/Network/assets/125638408/fba55ac0-4d4a-4094-8261-7f7d1baa4e2c)

16 byte xếp thành ma trận 4x4 
scrip : 
def bytes2matrix(text):
    """ Converts a 16-byte array into a 4x4 matrix.  """
    return [list(text[i:i+4]) for i in range(0, len(text), 4)]

def matrix2bytes(matrix):
    """ Converts a 4x4 matrix into a 16-byte array.  """
    return bytes(sum(matrix, []))

matrix = [
    [99, 114, 121, 112],
    [116, 111, 123, 105],
    [110, 109, 97, 116],
    [114, 105, 120, 125],
]

ta thu được flag : print(matrix2bytes(matrix)) 



RSA : 


![image](https://github.com/hieubmt1112004/Network/assets/125638408/6b791270-4129-48ef-aa01-b78cf5a15048)


Bài này chỉ cần dùng hàm pow trong python ta dễ dàng tính được kết quả của phép tính : print(pow(101, 17, 22663)) 
















