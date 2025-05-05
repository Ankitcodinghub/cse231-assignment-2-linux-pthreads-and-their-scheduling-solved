# cse231-assignment-2-linux-pthreads-and-their-scheduling-solved
**TO GET THIS SOLUTION VISIT:** [CSE231 Assignment 2-Linux pthreads and their scheduling Solved](https://www.ankitcodinghub.com/product/cse231-assignment-2-linux-pthreads-and-their-scheduling-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101089&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE231 Assignment 2-Linux pthreads and their scheduling&nbsp;Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Linux pthreads and their scheduling

1.1 Thread scheduling

This exercise is to show you how to use Linux’s scheduling policies for three threads. You need to launch three threads, each of which relies on three different functions, countA(), countB() and countC(). Each function does the same thing, i.e. counts from 1 – 232. The following should be the detailed specification of each of the threads, to being with:

<ol>
<li>Thread 1 (call it Thr-A()): Uses SCHED OTHER scheduling discipline with standard priority (nice:0).</li>
<li>Thread 2 (call it Thr-B()): Uses SCHED RR scheduling discipline with default priority.</li>
<li>Thread 3 (call it Thr-C()): Uses SCHED FIFO scheduling discipline with default priority.</li>
</ol>
Each of these threads must time the process of counting from 1 – 232. You can use the clock gettime() function for obtaining the actual time ticks that can be used to compute how long it took to complete a function.

We require you benchmark these three schedulers by change the schedul- ing priorities of the three threads (keeping the scheduling priorities the same), against the counting program.

For these cases, you would require to rely on pthread schedsetparam() and related functions for the same. You would require to generate histograms show- ing which scheduler completes the task when, depending upon the scheduling policy. You may choose different colors for the histogram bars, with one axis showing the time to complete, and the other showing the thread priorities. Of course, you cannot plot for all possible values of priorities; you would require to choose only some.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.2 Process scheduling

This part of the exercise, involves creating three process, instead of the three threads. Each of these process should involve compiling a copy of the Linux ker- nel source (with the minimal config shared by the TAs earlier). The three pro- cesses should be created with fork() and thereafter the child processes should use execl() family system calls to run a different a different bash script, each of which should be having the commands to compile a copy of the kernel. To time the execution, the parent process could get the clock timestamp (using clock gettime()) before the fork and after each process terminates (the event of which could be identified when the blocking system call waitpid()) returns.

What to submit/rubric.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

2.

3.

4.

5. 6.

</div>
<div class="column">
Successful compilation of the program. [Successfully compilation of

all the three programs: 10 points. No points for programs that

do not compile.]

The program where three threads Thr-A, Thr-B and Thr-C are being created and they invoke their respective count functions that does the basic

job of counting correctly. [Programs run correctly as expected: 10 points. No points for programs do not do the tasks correctly.] Appropriately used system calls to create processes and threads, along with the system calls to set the scheduling discipline and their priori- ties.[On use the appropriate system calls in the code: 20 points. Only 10 points to be awarded if the system calls to create pro- cess/thread, the calls to set the scheduling discipline and prior- ities is not used.] Program/threadruntimesandtheirvariationsduethedifferentprocess/thread scheduling policies and priorities along with their histogram plot showing

the same. [On fully reproducible behaviour: 30 points. If behav- ior is not fully reproducible but the runtimes as controlled by the scheduler is predictable and exaplinable : 20 points. Otherwise no points.]

Makefile to compile the above programs.[Fully functioning Makefile: 5 points.]

README/Write-up describing the program logic used for achieving the above (no more than one page)and an explanation of the outcomes of the tests/measurements.[5 points]

Kernel memory copy (kernel 2d memcpy()) (To- tal points: 70).

</div>
</div>
<div class="layoutArea">
<div class="column">
This exercise aimed to test your understanding how system calls work. You need to write a system call, kernel 2d memcpy(), which copies one 2-D float- ing point matrix to another. You would require using kernel functions like

copy from user() and copy from user() to read data bytes from user space and write back to user space. In other words, this is a version of memcpy() that relies on the kernel to do the necessary copy operations, which are otherwise usually done directly in the user space (using the standard C library routines).

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
What to submit/rubric.

<ol>
<li>The diff between the stock kernel and the kernel with your appropriate system call. This diff could be patched into the stock kernel code so as to achieve the required functionality (i.e. the system call) and used eventually. [Successfully compilation of the patched kernel: 50 points. No partial points.]</li>
<li>A sample program to test the above system call. In the program you could hard-wire the source 2-D matrix (i.e. no need to take input from user at runtime or via a file). [Program that correctly calls the system call with all the appropriate parameters and does the copy, provided (1) above works i.e.:10 points. Program compiles (as well as (1) above works), but copying is unsuccessful: 5 points.]</li>
<li>README/Write-up describing the program logic used for achieving the above (no more than one page). [5 points]</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
