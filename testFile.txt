cd /d e:\project\wiley\source6.2\hybwiley\hybris\bin\platform\
call setantenv.bat

call ant clean all -Dconfig=local > output33333.txt
call hybrisserver.bat debug > output2222.txt