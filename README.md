# What-I-Learn-Week-13

# *oops - using functions stack and queue with pop, and shift.

(ex)
const Stack = function() {
  return{
    items: [],
    add: function(item){
      this.items.push(item);
    },
    remove: function(){
      return this.items.pop();
    },
    peek: function(){
      return this.items[this.items.length - 1];
    },
  }
}


# *lil - Implement a little Linked List according to the test.

(ex)
const Lil = function(){
  return{
    head: null,
    addToStart: function(){
      if NewNode 

    }
  }

# double-lil - Refactor until the loops. Continuation fromn lil.

(ex)
 addToStart: function(value) {
      const newNode = Node(value);

      if (this.head === null) {
        this.head = newNode;

        return;
      }

      newNode.next = this.head;
      this.head.previous = newNode;
      this.head = newNode;

    },

# *graderaide - set property value.

(ex)
const Grade = (assignment, score) =>{
  return{
    assignment: assignment,
    score: score,
  }

}
