<h1>🏗️ libft - Your First C Library!</h1>

  

<h2>📌 What is libft?</h2>

libft is a custom standard library built from scratch as part of the 42 School curriculum. It includes essential functions that extend the capabilities of C’s standard library, allowing better control and flexibility when handling strings, memory, linked lists, and more.

Think of libft as your personal toolkit for future projects! 🛠️

<h2>🚀 Features</h2>

✅ Reimplementation of standard C library functions (strlen, strcpy, strcat, etc.)✅ Memory management functions (calloc, realloc, memcpy, etc.)✅ Custom utility functions (ft_itoa, ft_split, ft_strjoin, etc.)✅ Linked list manipulation functions (ft_lstnew, ft_lstadd_back, ft_lstmap, etc.)✅ Bonus part included! 🎉

<h2>🛠️ How to Use</h2>

<h3>1️⃣ Clone the repository:</h3>

$ ```git clone https://github.com/yourusername/libft.git```
$ ```cd libft```

<h3>2️⃣ Compile the library:</h3>

$ ```make```

<h3>3️⃣ Include it in your project:</h3>

```#include "libft.h"```

<h3>4️⃣ Link it with your program:</h3>

$``` gcc my_program.c -L. -lft -o my_program```

<h3>📂 Files Structure</h3>

<h3>📁 libft</h3>
├── src/         # Source files of libft functions
├── includes/    # Header file (libft.h)
├── Makefile     # Compilation script
├── README.md    # You’re reading it now!

<h2>🎯 Example Usage</h2>

Remember to:```
#include "libft.h"
#include <stdio.h>```
On top of .c file.

then:

```
int main()
{
    char *str = ft_strdup("Hello, libft!");
    printf("%s\n", str);
    free(str);
    return 0;
}
```
<h3>🎓 Why libft Matters?</h3>

📌 You’ll master memory management 🧠📌 You’ll sharpen your understanding of pointers 🖇️📌 You’ll create reusable functions for future projects 🔁📌 It’s your first step toward becoming a C pro! 🚀

🤝 Contributing

Want to improve libft? Feel free to fork and submit a PR! 💡

📜 License

This project is released for educational goals. Do not copy the project unless you want to get "Cheating" of "-42" 📝

📢 Acknowledgments

Big thanks to 42 School for the challenge and all the fellow cadets who helped debug my code! 🚀

Happy coding! 💻🔥

