Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > If to prosesses happens in parallell they run at the same time. You need a multicore prosessor to do this. 
 Concurrensy means that two tasks can start, run and in overlapping time periods (not simultaneously).
 
 ### Why have machines become increasingly multicore in the past decade?
> To preforme more tasks simontaniously. Prallelism is not possible om a single core prosessor. 
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > %%%%%%
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > %%%%%%
 
 ### What is the conceptual difference between threads and processes?
 > A process is a program that has been loaded into memory along with all the resources it needs to operate. 
 > A thread is the unit of executions within a process. 
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > Fiber/Green Thread: lightweight thread, sceduled by a runtime library or virtual machine instead of the OS. They are managed in user space instead of kernel space, enabling them to work in environments that do not have native thread support.
 > Coroutine: A component that allows a subroutine to have multiple entry points for suspending and resuming execution. Can exit by calling other corutines (unlike subrutines).
 
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > *Your answer here*
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*



 
 
 
 
