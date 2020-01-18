# Algoritma-Pertemuan-3
hei guys!! kali ini saya akan memberikan beberapa tips atau tutorial bagaimana proses pembuatan coding atau program sederhana mengenai cara kerja pada logaritma, maaf aja nih kalo tutorialnya sedikit ngebosenin tapi next time akan aku bikin semenarik mungkin sehingga kita semua bisa belajar bareng bikin coding. pantau aja terus chanel ini karena disini kalian bisa menambah wawasan seputar dunia informatika

N=int(input("Banyaknya Suku ="))
total=0
print("for :")
for i in range(1,N):
    total+=i
    print(i," + ",end="")
total+=N
print(N,"=",total)

print("while :")
i=1;total=0
while i<N:
    total+=i
    print(i," + ",end="")
    i+=1
total+=i
print(i,"=",total)
