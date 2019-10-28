# mergesort


def merge_sort (A):
    merge)sort2(A, 0, len(A)-1)

def merge_sort2(A, first, last):
    if first < last:
        middle = (first+last)/2
        merge_sort2(A, first, middle)
        merge_sort2(A, middle+1, last)
        merge(A, first, middle, last)
def merge (A, first, middle, last):
    L=[first:middle]
    R=[middle:last+1]
    L.append(99999)
    R.append(99999)
    i=j=0
    for k in range (first, last+1):
        if l[i] <= R[J]:
            A[k] = L[I]
            i+ = 1
         else
            A[k] = R[j]
            J+ =1
