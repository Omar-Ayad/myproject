# myproject
The it is test repo
print("Welcome To our App")
create=input("To craete a new account press enter")






    print("Welcome To our App")
    create=input("To craete a new account press enter")
    
    if create=="":
      print("Pleas enter your informatin")
      
      name=input("Enter your name: ")
      age=int(input("Enter your age: "))
      
      if age>=18:
        print("You can use our app")
    
        email=input("Enter your Email: ")
        Password=input("Enter a strong passwored: ")
    
        print("your account has created")
        print("Now you can login")
      
        email1=input("Enter your Email: ")
        Password1=input("Enter your Password: ")
    
        if email1==email and Password1==Password:
          print("""Welcome!
            We are happy to have you with us. Get ready to discover great features 
            and a seamless experience . Go ahead and get started now!""")
          
          
          print('Welcome to your librery')
          books=[]
          wich_books=[]
    
          first_book=input("enter your book own:\n")
    
          if first_book:
                
                books.append(first_book)
                second_book=input("Enter the name of anthor book you own or press Enter to skip :\n")
            
                if second_book:
                    books.append(second_book)
                print(books)
                
                else:
                    ٍprint(f"your have book{books} ")
                
                
                third_book=input("Enter the name of book you wich have in the future :\n")
                wich_books.append(third_book) 
                forth_book= input("Enter the name of anthor book you wich have in the futur or press enter to skip:\n")  
                
                if forth_book:
                    wich_books.append(forth_book)
                    print(f"your wich  books are{wich_books} ")
                
                else:
                    print(f"your books are{wich_books} ")   
                
                five_book=input("Enter book a book from wich_list you have :\n")
                books.append(five_book)
                
                print(f" Update Library:{books}")
                wich_books.remove(five_book) 
                
                print(f" Update Wishlist{wich_books}")
                book_donate=input("Enter a book you want donate : \n ")
                books.remove(book_donate)
                
                print(f"Final Library after Donations{books}")    
    
          else:
                print("You forgot to write the name of the book.")
    
        else:
            print("Sorry, your email or password is wrong")
    
      else:
        ("Sorry you can't use our app")  
    
    else:
      print("Sorry, you can't create an account")
