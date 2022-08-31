# File_Zipper
This project is based on Huffman Coding Algorithm , a lossless, bottom-up compression algorithm. It can compress(encode) and decompress(decode) any text files.

For Compressing the inputfile , first open the directory in which the files are present in powershell and use the command 

    g++ encode.cpp huffman.cpp -o main
 
 This will create the main.exe file and then to create the compressed file use the command 
 
    ./main inputFile.txt compressedFile.huf
  
  This command will compress the input file to .huf file 
  
  Now to decompress the file use the two commands as
  
      g++ decode.cpp huffman.cpp -o main
   
    ./main compressedFile.huf outputFile.txt
