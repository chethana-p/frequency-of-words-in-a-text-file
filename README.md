# frequency-of-words-in-a-text-file
#counts the frequency of each word in a file
def word_count(fname):
  with open(fname)as f:
     return (f.read().split())
  
 def freq(str):
  str2=[]
   for i in str:
       if i not in str2:
           str2.append(i)
   for i in range(0,len(str2)):
       print("frequency of ",str2[i],"is",str.count(str2[i]))
       
       
 def main():
    str=word_count("test.txt")#function call
    freq(str)#function call
    
  if __name=="__main__":
      main()
      
      
