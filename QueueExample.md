from collections import deque
my_list = [1, 2, 3, 4, 5]
my_queue = deque(my_list)
my_queue.append(6)  # adds 6 to the right end of the queue
my_queue.appendleft(0)  # adds 0 to the left end of the queue
print(my_queue)  # prints deque([0, 1, 2, 3, 4, 5, 6])
my_queue.pop()  # removes 6 from the right end of the queue
my_queue.popleft()  # removes 0 from the left end of the queue
print(my_queue)  # prints deque([1, 2, 3, 4, 5])
