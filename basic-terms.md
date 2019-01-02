# Composing term that is going to out in developer interview.

## Terms 

1. *Synchronous and asynchronous from an OS perspective*

Synchronous is waiting other working before finishing. Asynchronous don’t care other thread. In other word, if you need to   share resource, you should use synchronous method. Implementation of synchronous method are Mutex and Semaphore. 

Mutex
	MUTual Exclusion(상호배제)
	A Technology is that  Running time of Threads that have Critical section run independently so that they don’t overlap 
	a objet owned by thread, so there is a ownership in mutex. Mutex allow only one thread to access resource.

Semaphore
	simple counter that is presented resource status
	how many object can they access resource!
	signaling mechanism. It allows a number of thread to access shared resource.

2. *Parallel process vs distributed process*
- parallel process
	- to deal with lots of task  at the same time.
- distributed process
	- deal with one task by several people(?) at the same time
	- Mapreduce is representative example

3. *Callback function*
- passing a function that points to next execution point via a parameter and function that convey callback function execute this callback function in specific situation.
- 일반 함수는 필요할때 쓰고, 콜백 함수는 특정 이벤트가 발생하면 알아서 호출되는것 
Normal function use when they need, Callback function is called when specific event occur.

4. *Polymerphism.*
-  다형성
- The ability to have diverse shape. in other words, it is the concept that expands function through inheritance.

5. *0 is false,1 is true*

6. *JIT(Just In Time) compiler* 
- how to instantly compile what you need part at running the program point(프로그램을 실행하는 시점에서 필요한 부분을 즉석에서 컴파일하는 방식)

7. *Variable notation*
- underbarCase
	- custom_name
- camelCase
	- customName
- pascalCase
	- CustomName
- HungarianCase
	- [variable type]+pascalcase
	- iCustomName


## Reference
- http://yamalab.tistory.com/75
