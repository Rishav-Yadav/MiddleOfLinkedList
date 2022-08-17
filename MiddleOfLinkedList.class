


    class LinkedListNode<T> {
        T data;
        LinkedListNode<T> next;
    
        public LinkedListNode(T data) {
            this.data = data;
        }
    }


public class Solution {
    
    public static LinkedListNode<Integer> midPoint(LinkedListNode<Integer> head) {

          LinkedListNode<Integer> fast=head,slow=head;
       
           while(fast!=null&&fast.next!=null&&fast.next.next!=null){
           
           fast=fast.next.next;
            slow=slow.next;
       
                }
  
  return slow;
    }

}
