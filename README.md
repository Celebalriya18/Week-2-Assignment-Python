def average(array):
    # your code goes here
    
    total = 0
    for i in set(array):
        total = total + i
        
    average = total / len(set(array))
    return average

if __name__ == '__main__':
