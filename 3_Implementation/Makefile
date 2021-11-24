# Name of the project
PROJECT_NAME = Customer_billing_System



# All source code files
SRC = project_main.c\
src/customer_billing.c


INC = inc
all.exe : $(SRC) 
	gcc $^ -I$(INC) -o $@

run : all.exe
	./all.exe

clean:
	del all.exe


