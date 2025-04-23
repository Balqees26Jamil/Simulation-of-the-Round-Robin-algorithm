خوارزمية راوند روبين (Round-Robin) هي خوارزمية جدولة (Scheduling) تستخدم لتوزيع الأعمال أو المهام بالتساوي بين مجموعة من الموارد أو الأجهزة.
تعمل الخوارزمية على مبدأ التناوب بين جميع المهام بشكل دوري، حيث يتم تخصيص كل مهمة لفترة زمنية معينة تُسمى Time Quantum، وبعد انتهاء هذه الفترة، يتم الانتقال إلى المهمة التالية في الدور.
يتم تكرار هذه الدورة حتى تنتهي جميع المهام.

تستخدم خوارزمية Round-Robin بشكل رئيسي في أنظمة تشغيل الحاسوب لإدارة العمليات، حيث تتيح توزيع المعالج بشكل عادل بين العمليات المختلفة.



____________________________________________________________________



The Round-Robin algorithm is a scheduling algorithm used to distribute tasks or jobs evenly across a set of resources or processes.
It operates on the principle of rotating through all tasks in a cyclic manner, where each task is allocated a fixed time slice, called a Time Quantum. After this time slice is over, the next task in the cycle is processed.
This cycle repeats until all tasks are completed.

The Round-Robin algorithm is primarily used in operating systems to manage processes, ensuring that the processor is shared equally among different processes.

