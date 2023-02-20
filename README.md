class Solution {
    public int mostWordsFound(String[] sentences) {
       int max=0;
       for(int i=0;i<sentences.length;i++)
       {
           String sentence=sentences[i];// ["alice and bob love leetcode"]
           String words[]=sentence.split(" ");
           int words_count=words.length;//5
           if(words_count>max)//6>5
           {
               max=words_count;//6
           }
       }
       return max; 
    }
}
