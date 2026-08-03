danh_sach_cong_viec=[]
def menu():
    print ("=====TO DO LIST=====")
    print ("1.Them cong viec")
    print("2.Xem cong viec")
    print("3.Hoan thanh cong viec cuoi cung")
    print("4.Xoa toan bo danh sach")
    print("5.Xoa cong viec theo ten:")
    print("0. Thoat")
def nhap_lua_chon():
    while True:
        try:
            lua_chon = int(input("Chon mot so: "))
            return lua_chon
        except:
            print("Vui long nhap so!")
menu()
lua_chon = nhap_lua_chon()
def them_cong_viec():
    cong_viec= input("Nhap cong viec:")
    if cong_viec:
        danh_sach_cong_viec.append(cong_viec)
        print("Da them cong viec",cong_viec)
    else:
        print("Chua them cong viec")
def xem_danh_sach():
    print("=====DANH SACH CONG VIEC=====")
    for i in danh_sach_cong_viec:
        print(i)
    print("=============================")
def hoan_thanh_cong_viec():
    if len(danh_sach_cong_viec)>0:
           danh_sach_cong_viec.pop()
           print("Hoan thanh cong viec",danh_sach_cong_viec)
    else:
        print("Chua hoan thanh cong viec")
def xoa_tat_ca():
    danh_sach_cong_viec.clear()
    print("Hoan thanh tat ca cong viec",danh_sach_cong_viec)


def xoa_theo_ten():
    ten=input("Nhap ten cong viec can xoa:")
    if ten in danh_sach_cong_viec:
        danh_sach_cong_viec.remove(ten)
        print("Cong viec con lai",danh_sach_cong_viec)
    else:
        print("Khong tim thay cong viec!")
    
while lua_chon!=0:
    if lua_chon==1:
        them_cong_viec()
    elif lua_chon==2:
        xem_danh_sach()
    elif lua_chon==3:
        hoan_thanh_cong_viec()
    elif lua_chon==4:
        xoa_tat_ca()
    elif lua_chon==5:
        xoa_theo_ten()
    else:
        print("Vui long chon lai")
    menu()
    lua_chon=nhap_lua_chon()
if lua_chon==0:
    print("Thanks for using the app")
