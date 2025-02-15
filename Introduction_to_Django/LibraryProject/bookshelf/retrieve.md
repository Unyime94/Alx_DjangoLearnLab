from books.models import Book

book = Book.objects.get(title="1984")

print("Title:", book.title)
#Output: Title: 1984

print("Author:", book.author)
#Output: Author: George Orwell

print("Publication Year:", book.publication_year)
#Output: Publication Year: 1949
