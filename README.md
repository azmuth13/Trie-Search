# Trie-Search
https://trusting-wright-17c489.netlify.app/


**A demo on Trie data structure**

What is a trie?

A trie is a tree-like data structure whose nodes store the letters of an alphabet. By structuring the nodes in a particular way, words and strings can be retrieved from the structure by traversing down a branch path of the tree.

**Building the Trie**
Unlike C++ where we use pointer array for each node, in javaScript we can use regular objects as simplified Hashtables. 

```JavaScript


TrieNode {
    this.value
    this.isWord
    this.addChild = function(){
      this[nextLetter] = new TrieNode()
    }

    this.a = TrieNode {}
    this.b = TrieNode {}
    this.c = TrieNode {}
    ...
}

```

**Searching a word**
search.js include both linear search and TrieSearch to compare their efficiency. When a user search the result will come from TrieSearch, but both searches will run sequentially to see the advantage of logarithmic time search over linear time search.

**Screenshots**

![Screenshot (426)](https://user-images.githubusercontent.com/72400473/127738189-91406a76-86ae-4a3d-823f-a1e3612f1be4.png)



![Screenshot (427)](https://user-images.githubusercontent.com/72400473/127738194-ed2d3a18-3087-4f1b-a8d6-af1799682fc5.png)



![Screenshot (428)](https://user-images.githubusercontent.com/72400473/127738198-0bc3a105-e4c0-4cb9-836a-00447bb2f959.png)



![Screenshot (429)](https://user-images.githubusercontent.com/72400473/127738202-71453bfe-e8e5-417b-ab12-dda672ef241e.png)


