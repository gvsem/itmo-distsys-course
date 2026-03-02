## Список литературы

На нашем курсе нет обязательной литературы, но если вам интересна область распределенных
систем и вычислений, вам могут понравиться книги и статьи в этом разделе.

### Статьи для домашнего чтения

> - [L. Lamport - Time, clocks, and the ordering of events in a distributed system](https://dl.acm.org/doi/10.1145/359545.359563)

> - [Y. Saito, M. Shapiro – Optimistic replication](https://dl.acm.org/doi/abs/10.1145/1057977.1057980)

> - [M. Kleppmann et al. – Local-first software: you own your data, in spite of the cloud](https://doi.org/10.1145/3359591.3359737) (Local-first манифест)

> - [W. Vogels – Eventually consistent](https://doi.org/10.1145/1435417.1435432)

> - [M. Shapiro et al. – A comprehensive study of Convergent and Commutative Replicated Data Types](https://inria.hal.science/inria-00555588) (CRDT)

> - [L. Lamport – The part-time parliament](https://doi.org/10.1145/279227.279229) (PAXOS)

> - [D. Ongaro, J. Ousterhout – In search of an understandable consensus algorithm](https://www.usenix.org/system/files/conference/atc14/atc14-paper-ongaro.pdf) (RAFT)

> - [M. Fischer, N. Lynch, M. Paterson – Impossibility of Distributed Consensus with One Faulty Process](https://www.cs.princeton.edu/courses/archive/spr22/cos418/papers/flp.pdf) (FLP-теорема)

### Классические учебники

> - A. Tanenbaum, M. van Steen – Distributed Systems: Principles and Paradigms

Известный по своим "толстым книгам с черно-золотой обложкой", Таненбаум
является автором problem-driven учебника по распределенным системам – акцент на
модельных постановках проблем и их обсуждении.

> - G. Colouris – Distributed systems: Concepts and Design

Добротный учебник с вопросами и заданиями после каждой главы, который
освещает самый широкий ряд теоретических и практических вопросов.

> - M. Kleppmann – Designing Data-Intensive Applications

"Кабанчик" – классическая книга о распределенных хранилищах и репликации с хорошей библиографией в конце каждой главы. Несмотря на критику на Хабре вида "не читал, но осуждаю" или "многа букав" – книга написана максимально популярно и доступно
из всех возможных способов.

> - M. Perrin – Distributed Systems. Concurrency and Consistency

Малоизвестный авторский учебник по распределенкам, своей любовью к постановке
и рассмотрению теоретических проблем похожий на учебник Танненбаума.
Замечательно обобщены модели согласованности.

> - M. Herlihy et al. – The art of multiprocessor programming

Немного не относящийся к делу, но все же классический учебник о параллельном программировании: рассматриваются примитивы синхронизации, гонки, многопоточные алгоритмы и т.п.

> - А. Петров – Распределенные данные. Алгоритмы работы современных систем хранения информации

Замечательная книга о принципах организации СУБД (в частности, в сторону B-Tree, LSM) и распределенных вычислениях (Map-Reduce).

### Теоретический минимум

Распределенные системы – это набор сюжетов из разных предметных областей, которым соответствуют различные термины. В этом списке представлен некоторый минимальный список терминов, которое полезно знать о распределенных системах сегодня.

- Консенсус. Консенсусное число. Кворум. Выбор лидера. Атомарная рассылка. PAXOS, RAFT.

- Оптимистическая и пессимистическая репликация. Глобальная блокировка, распределенная блокировка, optimistic conccurrency control. Операциональные преобразования (OT). Бесконфликтно реплицируемые типы данных (CRDT).

- Модель согласованности: строгая, слабая, в конечном счете, сессионная. Сильная конечная согласованность.

- Часы и время. Часы реального времени, монотонные часы, логические часы.
Часы Лампорта, векторные часы. Теорема о минимальности векторных часов.

- FLP-, CAP-, PACELC- теоремы.

- REST, gRPC, RPC. Микросервисная архитектура. Трансляторы json-, proto- спецификаций в заглушки.

- Распределенные файловые системы: NFS, GFS, BigTable, IPFS

- Инфраструктура больших данных и стриминг: MapReduce, Hadoop, Spark, YTsaurus

[список будет дополняться...]