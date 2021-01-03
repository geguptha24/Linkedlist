# Linkedlist

class Node: # creating a indivudal nodes

  def __init__(self,data):
  self.data = data
  self.ref = None
  
class Linkedlist: # head None
  def __init__(self):
    self.head = None
  
   #checking the node is empty or not if it is empty it prints "the linked list is empty" else it print the linekd list one by one
  
  def print(self):
    if self.head is None:
      print('the linked list is empty')
     else:
     n = self.head
     while n != None:
     print(n.data)
     n = n.ref
l1 = Linkedlist()
l1.print()
  
