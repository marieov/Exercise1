Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > If to prosesses happens in parallell they run at the same time. You need a multicore prosessor to do this. 
 Concurrensy means that two tasks can start, run and in overlapping time periods (not simultaneously).
 
 ### Why have machines become increasingly multicore in the past decade?
> To preform more tasks simontaniously. Prallelism is not possible om a single core prosessor. 
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > (Not sure if I understood the question.)
 Simultaneous execution of transactions over a shared database can create several data integrity and consistency problems. E.g lost updates, uncommitted data, and inconsistent retrievals. Concurrency help in solving these problems. 
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 > Scaling the application to concurrent and parallel mode is very easy when working with Go. Simply append the "go" keyword to the function and you can quickly scale up the application execution.
 
 ### What is the conceptual difference between threads and processes?
 > A process is a program that has been loaded into memory along with all the resources it needs to operate. 
 > A thread is the unit of executions within a process. 
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > Fiber/Green Thread: lightweight thread, sceduled by a runtime library or virtual machine instead of the OS. They are managed in user space instead of kernel space, enabling them to work in environments that do not have native thread support.
 > Coroutine: A component that allows a subroutine to have multiple entry points for suspending and resuming execution. Can exit by calling other corutines (unlike subrutines).
 
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > POSIX Threads (or Pthreads) is a POSIX standard for threads in C. 
 > GoRoutines are a Golang wrapper on top of threads, and managed by Go runtime rather than the OS. 
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > Adds int number of execution cores. Once we create Goroutines, they can be executed together in different cores, enabling parallel processing and speeding up the application.



 
 
 
 
