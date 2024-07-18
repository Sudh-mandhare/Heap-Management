
# Virtual Heap Simulation

This project is simulation of heap using stack as a primary data structure.The projects aims to understand the way heap management is done within systems.The project simulate various functionns like **allocating memory** onto heap, **de-allocating** it and **display the addresses of the attocated and free memory spaces**.

Also some internal functions like **Merge free spaces** which merges two adjacent free memory blocks so as to deal with fragmentation losses.
The project thus uses a simple yet efficient technique of **FIRST FIT** of memory allocation


## Run Locally

Clone the project

```bash
  git clone https://github.com/Sudh-mandhare/Heap-Management/blob/main/cpl2final.c
```

Go to the project directory

```bash
  cd Heap-Management
```

* Once done with installation - tweak the input as required to learn more about the possible memory fragmentations

For running the code 
* In Linux
```bash
  gcc cpl2final.c -o final
  ./final
```
* In Windows
```bash
  gcc cpl2final.c -o final.exe
  ./final.exe
```




## Acknowledgements

Special thanks to my friend Sumedh Ganpatye for his valuable feedback on the code
## Future Enhancements

* The heap simulation can be done in a more efficient way using Fibonacci method of alloction to decrease memory fragmentation.
