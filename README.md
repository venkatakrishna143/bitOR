# bitOR

def game_with_number (arr, n) :
for i in range(0,n-1):
arr[i]=(arr[i] | arr[i+1])
return arr
             
