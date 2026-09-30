## Day 02 File and Directory Management

                                                 How to Create File
                                      ___________________|____________________
                                      |           |              |            |
                                     cat         touch          vi/vm        nano

**Cat** - Cat command is a universal tool, which help to copy standard input to Standar Output.    
        - The main purpose of cat command for concatinates the Files
        - Cat command is used for
            1. Create a File- Using cat command we create file but can't edit the file.
               cat > file
            2. Concatinate the files - Two or More files Concatinate in one file using cat command.
               cat file1 file2 > all
            3. Copy the file 1 data into file2 using cat command
               cat file1 > file2
            4. View the file1 data
               cat file1
            5. tac  - We used this command for viewing the file data in reverse
               1.cat > file3
                hellow
                namaste
                ctrl+d - this used for exit
               2.cat file3
                 o/p- hellow
                      namaste
                3.tac file3
                 o/p- namaste
                      hellow
 **touch**- 
