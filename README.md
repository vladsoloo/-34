### Соломахин Владислав
### Урок 34 

1) процессор — это основной компонент вычислительных устройств, выполняющий обработку данных и управление всеми задачами системы. Его ещё называют центральным процессором, так как он выполняет основную работу в компьютере.

2) в состав центрального процессора (ЦП) входят: АЛУ, УУ шины данных, регистры, кэш-память и счетчики команд

3) арифметико-логическое устройство. В простейшем случае АЛУ состоит из двух регистров, сумматора и схем управления операциями. 
Сумматор — логический операционный узел, выполняющий арифметическое сложение кодов двух чисел. При арифметическом сложении выполняются и другие дополнительные операции: учёт знаков чисел, выравнивание порядков слагаемых и тому подобное. Указанные операции выполняются в арифметическо-логических устройствах (АЛУ) или процессорных элементах, ядром которых являются сумматоры.

4) изменение флага ZF - чтобы не выполнять лишнюю команду сравнения

5) чтобы установить факт равенства или неравенства нулю сумматора с помощью логических операций с его битами, нужно:

А) Определить, какие биты представляет собой сумматор. Обычно в нём используются биты для слагаемых, бит для переноса и бит для суммы. Б) Применить логические операции к этим битам. В) Для проверки равенства нулю сумматора использовать операцию логического И (AND). Для этого необходимо выполнить логическое И между всеми битами сумматора. Если результат операции равен 0, то сумматор равен нулю. Г) Для проверки неравенства нулю сумматора использовать операцию логического ИЛИ (OR). Для этого необходимо выполнить логическое ИЛИ между всеми битами сумматора. Если результат операции не равен 0, то сумматор не равен нулю.

6) Математический сопроцессор — сопроцессор для расширения командного множества центрального процессора и обеспечивающий его функциональностью модуля операций с плавающей запятой, для процессоров, не имеющих интегрированного модуля.

7) стройство управления (УУ) отвечает за выполнение программы и согласование взаимодействий всех узлов компьютера. В современных компьютерах АЛУ и УУ изготавливаются в виде единой интегральной схемы — микропроцессора.

8) актом работы процессора называется выполнение одной машинной команды.

9) Генератор тактовых импульсов (генератор тактовой частоты) предназначен для синхронизации различных процессов в цифровых устройствах — ЭВМ, электронных часах, таймерах и других.

10) РОН — акроним от регистр общего назначения.Используются для хранения данных и выполнения различных арифметических и логических операций

11) Эти регистры называются EAX, EBX, ECX, EDX, ESI, EDI, EBP, ESP. Доступ к младшим 16 бит этих регистров выполняется независимо при использовании соответствующих имен 16-битных регистров: AX, BX, CX, DX, SI, DI, BP и SP.

12) Скорость процессора (часто называемая «тактовой частотой») – количество циклов, выполняемых процессором за одну секунду. Данный показатель выражается в герцах (Гц), где один герц соответствует одному циклу в секунду.

13) Большинство современных процессоров Intel, даже с меньшими частотами и с меньшим количеством ядер, производительнее большинства современных процессов AMD (RYZEN)

14) Из-за того, что на каждом такте процессор выполняет с помощью конвейера сразу несколько частей (этапов) команд, все пять команд выполняются за 7 тактов, а не за 15, как было бы при последовательном исполнении этой же цепочки команд.

Вопрос15) Разрядность определяет, сколько бит информации чип сможет обрабатывать за один такт. Чем выше, тем лучше система справляется с поставленной задачей.У нас имеется три критерия видов разрядности: функциональный (обработки, хранения и обмена), реализационный (физическая и архитектурная) и типовой (данных и адресов).Их характерезует количество информации (байт), которое можно передать за такт

16) команды пересылки данных; арифметические команды; логические команды; команды переходов.

17) Сокращенное число команд в архитектуре RISC, создает ситуации, когда на выполнение нескольких функций, приходится тратить несколько команд, в отличие от одной в архитектуре CISC.

18) Основными составными частями ЦП являются: арифметико-логическое устройство ( АЛУ ), устройство управления ( блок команд), быстродействующая постоянная (“не стираемая”) память

### ЗАДАЧИ
1) Z or N; б) not (Z or N) = not Z and not N
2) 60⋅109
3) дзынь дзынь
4) 232‐1 = 4 294 967 295
5) 4
6) 64 Гб
