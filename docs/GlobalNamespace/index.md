# Global Namespace



## Records

* [FPdbleword](FPdbleword.md)
* [Fmt](Fmt.md)
* [Tm](Tm.md)
* [Lock](Lock.md)
* [QLp](QLp.md)
* [QLock](QLock.md)
* [RWLock](RWLock.md)
* [Rendez](Rendez.md)
* [NetConnInfo](NetConnInfo.md)
* [Qid](Qid.md)
* [Dir](Dir.md)
* [Waitmsg](Waitmsg.md)
* [IOchunk](IOchunk.md)
* [PSlice](PSlice.md)
* [Completion](Completion.md)
* [Bin](Bin.md)
* [Biobuf](Biobuf.md)
* [Avl](Avl.md)
* [Avltree](Avltree.md)
* [Avlwalk](Avlwalk.md)


## Functions

### memccpy

*void * memccpy(void * , const void * , int , uint32_t )*

 mem routines

### memset

*void * memset(void * , int , size_t )*

### memcmp

*int memcmp(const void * , const void * , uint32_t )*

### memcpy

*void * memcpy(void * , const void * , size_t )*

### memmove

*void * memmove(void * , const void * , size_t )*

### memchr

*void * memchr(const void * , int , uint32_t )*

### strcat

*char * strcat(char * , const char * )*

 string routines

### strchr

*char * strchr(const char * , int )*

### strcmp

*int strcmp(const char * , const char * )*

### strcpy

*char * strcpy(char * , const char * )*

### strecpy

*char * strecpy(char * , char * , const char * )*

### strdup

*char * strdup(const char * )*

### strlcat

*size_t strlcat(char * , const char * , size_t )*

### strlcpy

*size_t strlcpy(char * , const char * , size_t )*

### strncat

*char * strncat(char * , const char * , int32_t )*

### strncpy

*char * strncpy(char * , const char * , uint32_t )*

### strncmp

*int strncmp(const char * , const char * , int32_t )*

### strpbrk

*char * strpbrk(const char * , const char * )*

### strrchr

*char * strrchr(const char * , int )*

### strtok

*char * strtok(char * , char * )*

### strlen

*int strlen(const char * )*

### strspn

*int strspn(const char * , const char * )*

### strcspn

*int strcspn(const char * , const char * )*

### strstr

*char * strstr(const char * , const char * )*

### cistrncmp

*int cistrncmp(const char * , const char * , int )*

### cistrcmp

*int cistrcmp(const char * , const char * )*

### cistrstr

*char * cistrstr(const char * , const char * )*

### tokenize

*int tokenize(char * , char ** , int )*

### runetochar

*int runetochar(char * , const Rune * )*

 rune routines

### chartorune

*int chartorune(Rune * , const char * )*

### runelen

*int runelen(Rune )*

### runenlen

*int runenlen(const Rune * , int )*

### fullrune

*int fullrune(const char * , int )*

### utflen

*int utflen(const char * )*

### utfnlen

*int utfnlen(const char * , int32_t )*

### utfrune

*char * utfrune(const char * , Rune )*

### utfrrune

*char * utfrrune(const char * , Rune )*

### utfutf

*char * utfutf(const char * , const char * )*

### utfecpy

*char * utfecpy(char * , char * , const char * )*

### runestrcat

*Rune * runestrcat(Rune * , const Rune * )*

### runestrchr

*Rune * runestrchr(const Rune * , Rune )*

### runestrcmp

*int runestrcmp(const Rune * , const Rune * )*

### runestrcpy

*Rune * runestrcpy(Rune * , const Rune * )*

### runestrncpy

*Rune * runestrncpy(Rune * , const Rune * , int32_t )*

### runestrecpy

*Rune * runestrecpy(Rune * , Rune * , const Rune * )*

### runestrdup

*Rune * runestrdup(const Rune * )*

### runestrncat

*Rune * runestrncat(Rune * , const Rune * , int32_t )*

### runestrncmp

*int runestrncmp(const Rune * , const Rune * , int32_t )*

### runestrrchr

*Rune * runestrrchr(const Rune * , Rune )*

### runestrlen

*int32_t runestrlen(const Rune * )*

### runestrstr

*Rune * runestrstr(const Rune * , const Rune * )*

### tolowerrune

*Rune tolowerrune(Rune )*

### totitlerune

*Rune totitlerune(Rune )*

### toupperrune

*Rune toupperrune(Rune )*

### tobaserune

*Rune tobaserune(Rune )*

### isalpharune

*int isalpharune(Rune )*

### isbaserune

*int isbaserune(Rune )*

### isdigitrune

*int isdigitrune(Rune )*

### islowerrune

*int islowerrune(Rune )*

### isspacerune

*int isspacerune(Rune )*

### istitlerune

*int istitlerune(Rune )*

### isupperrune

*int isupperrune(Rune )*

### malloc

*void * malloc(size_t )*

 malloc

### mallocz

*void * mallocz(uint32_t , int )*

### free

*void free(void * )*

### msize

*uint32_t msize(void * )*

### mallocalign

*void * mallocalign(uint32_t , uint32_t , int32_t , uint32_t )*

### calloc

*void * calloc(uint32_t , size_t )*

### realloc

*void * realloc(void * , size_t )*

### setmalloctag

*void setmalloctag(void * , uintptr_t )*

### setrealloctag

*void setrealloctag(void * , uintptr_t )*

### getmalloctag

*uintptr_t getmalloctag(void * )*

### getrealloctag

*uintptr_t getrealloctag(void * )*

### malloctopoolblock

*void * malloctopoolblock(void * )*

### print

*int print(const char * )*

### seprint

*char * seprint(char * , char * , const char * )*

### vseprint

*char * vseprint(char * , char * , const char * , va_list )*

### snprint

*int snprint(char * , int , const char * )*

### vsnprint

*int vsnprint(char * , int , const char * , va_list )*

### smprint

*char * smprint(const char * )*

### vsmprint

*char * vsmprint(const char * , va_list )*

### sprint

*int sprint(char * , const char * )*

### fprint

*int fprint(int , const char * )*

### vfprint

*int vfprint(int , const char * , va_list )*

### runesprint

*int runesprint(Rune * , const char * )*

### runesnprint

*int runesnprint(Rune * , int , const char * )*

### runevsnprint

*int runevsnprint(Rune * , int , const char * , va_list )*

### runeseprint

*Rune * runeseprint(Rune * , Rune * , const char * )*

### runevseprint

*Rune * runevseprint(Rune * , Rune * , const char * , va_list )*

### runesmprint

*Rune * runesmprint(const char * )*

### runevsmprint

*Rune * runevsmprint(const char * , va_list )*

### fmtfdinit

*int fmtfdinit(Fmt * , int , char * , int )*

### fmtfdflush

*int fmtfdflush(Fmt * )*

### fmtstrinit

*int fmtstrinit(Fmt * )*

### fmtstrflush

*char * fmtstrflush(Fmt * )*

### runefmtstrinit

*int runefmtstrinit(Fmt * )*

### runefmtstrflush

*Rune * runefmtstrflush(Fmt * )*

### fmtinstall

*int fmtinstall(int , int (*)(Fmt *) )*

### dofmt

*int dofmt(Fmt * , const char * )*

### dorfmt

*int dorfmt(Fmt * , const Rune * )*

### fmtprint

*int fmtprint(Fmt * , const char * )*

### fmtvprint

*int fmtvprint(Fmt * , const char * , va_list )*

### fmtrune

*int fmtrune(Fmt * , int )*

### fmtstrcpy

*int fmtstrcpy(Fmt * , const char * )*

### fmtrunestrcpy

*int fmtrunestrcpy(Fmt * , const Rune * )*

### errfmt

*int errfmt(Fmt * f)*

 error string for %r supplied on per os basis, not part of fmt library

### unquotestrdup

*char * unquotestrdup(const char * )*

 quoted strings

### unquoterunestrdup

*Rune * unquoterunestrdup(const Rune * )*

### quotestrdup

*char * quotestrdup(const char * )*

### quoterunestrdup

*Rune * quoterunestrdup(const Rune * )*

### quotestrfmt

*int quotestrfmt(Fmt * )*

### quoterunestrfmt

*int quoterunestrfmt(Fmt * )*

### quotefmtinstall

*void quotefmtinstall()*

### needsrcquote

*int needsrcquote(int )*

### srand

*void srand(int32_t )*

 random number

### rand

*int rand()*

### nrand

*int nrand(int )*

### lrand

*int32_t lrand()*

### lnrand

*int32_t lnrand(int32_t )*

### frand

*double frand()*

### truerand

*uint32_t truerand()*

### ntruerand

*uint32_t ntruerand(uint32_t )*

### getfcr

*uint32_t getfcr()*

 math

### setfsr

*void setfsr(uint32_t )*

### getfsr

*uint32_t getfsr()*

### setfcr

*void setfcr(uint32_t )*

### NaN

*double NaN()*

### Inf

*double Inf(int )*

### isNaN

*int isNaN(double )*

### isInf

*int isInf(double , int )*

### umuldiv

*uint32_t umuldiv(uint32_t , uint32_t , uint32_t )*

### muldiv

*int32_t muldiv(int32_t , int32_t , int32_t )*

### pow

*double pow(double , double )*

### atan2

*double atan2(double , double )*

### fabs

*double fabs(double )*

### atan

*double atan(double )*

### log

*double log(double )*

### log10

*double log10(double )*

### exp

*double exp(double )*

### floor

*double floor(double )*

### ceil

*double ceil(double )*

### hypot

*double hypot(double , double )*

### sin

*double sin(double )*

### cos

*double cos(double )*

### tan

*double tan(double )*

### asin

*double asin(double )*

### acos

*double acos(double )*

### sinh

*double sinh(double )*

### cosh

*double cosh(double )*

### tanh

*double tanh(double )*

### sqrt

*double sqrt(double )*

### fmod

*double fmod(double , double )*

### gmtime

*Tm * gmtime(int32_t )*

### localtime

*Tm * localtime(int32_t )*

### asctime

*char * asctime(Tm * )*

### ctime

*char * ctime(int32_t )*

### cputime

*double cputime()*

### times

*int32_t times(int32_t * )*

### tm2sec

*int32_t tm2sec(Tm * )*

### nsec

*int64_t nsec()*

### cycles

*void cycles(uint64_t * )*

### _assert

*void _assert(char * )*

### abs

*int abs(int )*

### atexit

*int atexit(void (*)(void) )*

### atexitdont

*void atexitdont(void (*)(void) )*

### atnotify

*int atnotify(int (*)(void *, char *) , int )*

### atof

*double atof(const char * )*

### atoi

*int atoi(const char * )*

### atol

*int32_t atol(const char * )*

### atoll

*int64_t atoll(const char * )*

### charstod

*double charstod(int (*)(void *) , void * )*

### cleanname

*char * cleanname(char * )*

### decrypt

*int decrypt(void * , void * , int )*

### encrypt

*int encrypt(void * , void * , int )*

### dec64

*int dec64(uint8_t * , int , const char * , int )*

### enc64

*int enc64(char * , int , const uint8_t * , int )*

### dec32

*int dec32(uint8_t * , int , const char * , int )*

### enc32

*int enc32(char * , int , const uint8_t * , int )*

### dec16

*int dec16(uint8_t * , int , const char * , int )*

### enc16

*int enc16(char * , int , const uint8_t * , int )*

### encodefmt

*int encodefmt(Fmt * )*

### exits

*void exits(const char * )*

### frexp

*double frexp(double , int * )*

### getcallstack

*void getcallstack(uintptr * , size_t )*

### getenv

*char * getenv(const char * )*

### getfields

*int getfields(char * , char ** , int , int , const char * )*

### gettokens

*int gettokens(char * , char ** , int , const char * )*

### getuser

*char * getuser()*

### getwd

*char * getwd(char * , int )*

### iounit

*int iounit(int )*

### labs

*int32_t labs(int32_t )*

### ldexp

*double ldexp(double , int )*

### longjmp

*void longjmp(jmp_buf , int )*

### mktemp

*char * mktemp(char * )*

### modf

*double modf(double , double * )*

### netcrypt

*int netcrypt(void * , void * )*

### notejmp

*void notejmp(void * , jmp_buf , int )*

### perror

*void perror(const char * )*

### postnote

*int postnote(int , int , const char * )*

### pow10

*double pow10(int )*

### putenv

*int putenv(const char * , const char * )*

### qsort

*void qsort(void * , int32_t , int32_t , int (*)(const void *, const void *) )*

### setjmp

*int setjmp(jmp_buf )*

### strtod

*double strtod(const char * , char ** )*

### strtol

*int32_t strtol(const char * , char ** , int )*

### strtoul

*uint32_t strtoul(const char * , char ** , int )*

### strtoll

*int64_t strtoll(const char * , char ** , int )*

### strtoull

*uint64_t strtoull(const char * , char ** , int )*

### sysfatal

*void sysfatal(const char * )*

### syslog

*void syslog(int , const char * , const char * )*

### time

*int32_t time(int32_t * )*

### tolower

*int tolower(int )*

### toupper

*int toupper(int )*

### ainc

*int32_t ainc(int32_t * )*

 atomic

### adec

*int32_t adec(int32_t * )*

### cas32

*int cas32(uint32_t * , uint32_t , uint32_t )*

### casp

*int casp(void ** , void * , void * )*

### casl

*int casl(uint32_t * , uint32_t , uint32_t )*

### _tas

*int _tas(int * )*

### _tas32

*int _tas32(int * )*

### lock

*void lock(Lock * )*

### unlock

*void unlock(Lock * )*

### canlock

*int canlock(Lock * )*

### qlock

*void qlock(QLock * )*

### qunlock

*void qunlock(QLock * )*

### canqlock

*int canqlock(QLock * )*

### _qlockinit

*void _qlockinit(void *(*)(void *, void *) )*

### rlock

*void rlock(RWLock * )*

### runlock

*void runlock(RWLock * )*

### canrlock

*int canrlock(RWLock * )*

### wlock

*void wlock(RWLock * )*

### wunlock

*void wunlock(RWLock * )*

### canwlock

*int canwlock(RWLock * )*

### rsleep

*void rsleep(Rendez * )*

### rwakeup

*int rwakeup(Rendez * )*

### rwakeupall

*int rwakeupall(Rendez * )*

### privalloc

*void ** privalloc()*

### privfree

*void privfree(void ** )*

### accept

*int accept(int , const char * )*

### announce

*int announce(const char * , char * )*

### dial

*int dial(const char * , const char * , char * , int * )*

### setnetmtpt

*void setnetmtpt(char * , int , const char * )*

### hangup

*int hangup(int )*

### listen

*int listen(const char * , char * )*

### netmkaddr

*char * netmkaddr(const char * , const char * , const char * )*

### reject

*int reject(int , const char * , const char * )*

### pushssl

*int pushssl(int , const char * , const char * , const char * , int * )*

  encryption

### pushtls

*int pushtls(int , const char * , const char * , int , const char * , char * )*

### getnetconninfo

*NetConnInfo * getnetconninfo(const char * , int )*

### freenetconninfo

*void freenetconninfo(NetConnInfo * )*

### _exits

*void _exits(const char * )*

### abort

*void abort()*

### access

*int access(const char * , int )*

### alarm

*int64_t alarm(uint64_t )*

### await

*int await(char * , int )*

### bind

*int bind(const char * , const char * , int )*

### brk

*int brk(void * )*

### chdir

*int chdir(const char * )*

### close

*int close(int )*

### create

*int create(const char * , int , uint32_t )*

### dup

*int dup(int , int )*

### errno2str

*char * errno2str(uint errno)*

### errstr

*int errstr(char * , uint )*

### exec

*int exec(const char * , char *const [] )*

### execl

*int execl(const char * )*

### fork

*int fork()*

### rfork

*int rfork(int )*

### fauth

*int fauth(int , const char * )*

### fstat

*int fstat(int , uint8_t * , int )*

### fwstat

*int fwstat(int , uint8_t * , int )*

### fversion

*int fversion(int , int , char * , int )*

### mount

*int mount(int , int , const char * , int , const char * , int )*

### unmount

*int unmount(const char * , const char * )*

### noted

*int noted(int )*

### notify

*int notify(void (*)(void *, char *) )*

### open

*int open(const char * , int )*

### fd2path

*int fd2path(int , char * , int )*

### pipe

*int pipe(int * )*

 extern	int	fdflush(int);

### pread

*int32_t pread(int , void * , int32_t , int64_t )*

### read

*int32_t read(int , void * , int32_t )*

### preadv

*int32_t preadv(int , IOchunk * , int , int64_t )*

### pwrite

*int32_t pwrite(int , const void * , int32_t , int64_t )*

### write

*int32_t write(int , const void * , int32_t )*

### pwritev

*int32_t pwritev(int , IOchunk * , int , int64_t )*

### r0

*int32_t r0()*

### readn

*int32_t readn(int , void * , int32_t )*

### readv

*int32_t readv(int , IOchunk * , int )*

### remove

*int remove(const char * )*

### sbrk

*void * sbrk(uint32_t )*

### oseek

*int32_t oseek(int , int32_t , int )*

### seek

*int64_t seek(int , int64_t , int )*

### segattach

*void * segattach(int , const char * , void * , uint32_t )*

### segbrk

*void * segbrk(void * , void * )*

### segdetach

*int segdetach(void * )*

### segflush

*int segflush(void * , uint32_t )*

### segfree

*int segfree(void * , uint32_t )*

### semacquire

*int semacquire(int32_t * , int )*

### semrelease

*int32_t semrelease(int32_t * , int32_t )*

### sleep

*int sleep(int32_t )*

### stat

*int stat(const char * , uint8_t * , int )*

### tsemacquire

*int tsemacquire(int32_t * , uint64_t )*

### wait

*Waitmsg * wait()*

### waitpid

*int waitpid()*

### writev

*int32_t writev(int , IOchunk * , int )*

### wstat

*int wstat(const char * , uint8_t * , int )*

### rendezvous

*void * rendezvous(void * , void * )*

### dirstat

*Dir * dirstat(const char * )*

### dirfstat

*Dir * dirfstat(int )*

### dirwstat

*int dirwstat(const char * , Dir * )*

### dirfwstat

*int dirfwstat(int , Dir * )*

### dirread

*int32_t dirread(int , Dir ** )*

### nulldir

*void nulldir(Dir * )*

### dirreadall

*int32_t dirreadall(int , Dir ** )*

### getpid

*int getpid()*

### getppid

*int getppid()*

### rerrstr

*void rerrstr(char * , uint )*

### sysname

*char * sysname()*

### werrstr

*void werrstr(const char * )*

### reallocarray

*void * reallocarray(void * base, size_t nel, size_t size)*

### psliceinit

*void psliceinit(PSlice * slice)*

### psliceclear

*void psliceclear(PSlice * slice)*

### psliceget

*void * psliceget(PSlice * slice, size_t i)*

### psliceput

*int psliceput(PSlice * slice, size_t i, void * p)*

### pslicedel

*int pslicedel(PSlice * slice, size_t i)*

### psliceappend

*void psliceappend(PSlice * s, void * p)*

### pslicelen

*size_t pslicelen(PSlice * slice)*

### pslicefinalize

*void ** pslicefinalize(PSlice * slice)*

### pslicedestroy

*void pslicedestroy(PSlice * slice)*

### query_mem

*void query_mem(const char * config_string, uintptr_t * base, size_t * size)*

 configstring functions. These are from riscv but the idea is so good it might have other uses. 

### query_rtc

*void query_rtc(const char * config_string, uintptr_t * mtime)*

### query_uint

*int query_uint(const char * configstring, char * name, uintptr_t * m)*

### complete

*Completion * complete(char * dir, char * s)*

*Defined at [complete.c#50](https://github.com/Harvey-OS/harvey/blob/main/complete.c#50)*

### freecompletion

*void freecompletion(Completion * )*

*Defined at [complete.c#31](https://github.com/Harvey-OS/harvey/blob/main/complete.c#31)*

### longestprefixlength

*int longestprefixlength(char * a, char * b, int n)*

*Defined at [complete.c#14](https://github.com/Harvey-OS/harvey/blob/main/complete.c#14)*

### strpcmp

*int strpcmp(const void * va, const void * vb)*

*Defined at [complete.c#40](https://github.com/Harvey-OS/harvey/blob/main/complete.c#40)*

### binalloc

*void * binalloc(Bin ** , uint32_t size, int zero)*

*Defined at [bin.c#56](https://github.com/Harvey-OS/harvey/blob/main/bin.c#56)*

### bingrow

*void * bingrow(Bin ** , void * op, uint32_t osize, uint32_t size, int zero)*

*Defined at [bin.c#87](https://github.com/Harvey-OS/harvey/blob/main/bin.c#87)*

### binfree

*void binfree(Bin ** )*

*Defined at [bin.c#109](https://github.com/Harvey-OS/harvey/blob/main/bin.c#109)*

### mkbin

*Bin * mkbin(Bin * bin, uint32_t size)*

*Defined at [bin.c#38](https://github.com/Harvey-OS/harvey/blob/main/bin.c#38)*

 allocator which allows an entire set to be freed at one time

### Bbuffered

*int Bbuffered(Biobufhdr * )*

### Bfildes

*int Bfildes(Biobufhdr * )*

### Bflush

*int Bflush(Biobufhdr * )*

### Bgetc

*int Bgetc(Biobufhdr * )*

### Bgetd

*int Bgetd(Biobufhdr * , double * )*

### Bgetrune

*int32_t Bgetrune(Biobufhdr * )*

### Binit

*int Binit(Biobuf * , int , int )*

### Binits

*int Binits(Biobufhdr * , int , int , uint8_t * , int )*

### Blinelen

*int Blinelen(Biobufhdr * )*

### Boffset

*int64_t Boffset(Biobufhdr * )*

### Bopen

*Biobuf * Bopen(char * , int )*

### Bprint

*int Bprint(Biobufhdr * , char * )*

### Bvprint

*int Bvprint(Biobufhdr * , char * , va_list )*

### Bputc

*int Bputc(Biobufhdr * , int )*

### Bputrune

*int Bputrune(Biobufhdr * , int32_t )*

### Brdline

*void * Brdline(Biobufhdr * , int )*

### Brdstr

*char * Brdstr(Biobufhdr * , int , int )*

### Bread

*int32_t Bread(Biobufhdr * , void * , int32_t )*

### Bseek

*int64_t Bseek(Biobufhdr * , int64_t , int )*

### Bterm

*int Bterm(Biobufhdr * )*

### Bungetc

*int Bungetc(Biobufhdr * )*

### Bungetrune

*int Bungetrune(Biobufhdr * )*

### Bwrite

*int32_t Bwrite(Biobufhdr * , void * , int32_t )*

### avlnext

*Avl * avlnext(Avlwalk * walk)*

*Defined at [avl.c#369](https://github.com/Harvey-OS/harvey/blob/main/avl.c#369)*

### avlprev

*Avl * avlprev(Avlwalk * walk)*

*Defined at [avl.c#388](https://github.com/Harvey-OS/harvey/blob/main/avl.c#388)*

### avlwalk

*Avlwalk * avlwalk(Avltree * tree)*

*Defined at [avl.c#354](https://github.com/Harvey-OS/harvey/blob/main/avl.c#354)*

### deleteavl

*void deleteavl(Avltree * tree, Avl * key, Avl ** oldp)*

*Defined at [avl.c#347](https://github.com/Harvey-OS/harvey/blob/main/avl.c#347)*

### endwalk

*void endwalk(Avlwalk * walk)*

*Defined at [avl.c#410](https://github.com/Harvey-OS/harvey/blob/main/avl.c#410)*

### insertavl

*void insertavl(Avltree * tree, Avl * new, Avl ** oldp)*

*Defined at [avl.c#244](https://github.com/Harvey-OS/harvey/blob/main/avl.c#244)*

### lookupavl

*Avl * lookupavl(Avltree * tree, Avl * key)*

*Defined at [avl.c#318](https://github.com/Harvey-OS/harvey/blob/main/avl.c#318)*

### mkavltree

*Avltree * mkavltree(int (*)(Avl *, Avl *) cmp)*

*Defined at [avl.c#231](https://github.com/Harvey-OS/harvey/blob/main/avl.c#231)*

### searchavl

*Avl * searchavl(Avltree * tree, Avl * key, int neighbor)*

*Defined at [avl.c#312](https://github.com/Harvey-OS/harvey/blob/main/avl.c#312)*

### singleleft

*void singleleft(Avl ** tp, Avl * p)*

*Defined at [avl.c#20](https://github.com/Harvey-OS/harvey/blob/main/avl.c#20)*

 In-memory database stored as self-balancing AVL tree. See Lewis & Denenberg, Data Structures and Their Algorithms.

### singleright

*void singleright(Avl ** tp, Avl * p)*

*Defined at [avl.c#46](https://github.com/Harvey-OS/harvey/blob/main/avl.c#46)*

### doublerightleft

*void doublerightleft(Avl ** tp, Avl * p)*

*Defined at [avl.c#70](https://github.com/Harvey-OS/harvey/blob/main/avl.c#70)*

### doubleleftright

*void doubleleftright(Avl ** tp, Avl * p)*

*Defined at [avl.c#77](https://github.com/Harvey-OS/harvey/blob/main/avl.c#77)*

### balance

*void balance(Avl ** tp, Avl * p)*

*Defined at [avl.c#84](https://github.com/Harvey-OS/harvey/blob/main/avl.c#84)*

### canoncmp

*int canoncmp(int cmp)*

*Defined at [avl.c#108](https://github.com/Harvey-OS/harvey/blob/main/avl.c#108)*

### _insertavl

*int _insertavl(Avl ** tp, Avl * p, Avl * r, int (*)(Avl *, Avl *) cmp, Avl ** rfree)*

*Defined at [avl.c#118](https://github.com/Harvey-OS/harvey/blob/main/avl.c#118)*

### successor

*int successor(Avl ** tp, Avl * p, Avl ** r)*

*Defined at [avl.c#151](https://github.com/Harvey-OS/harvey/blob/main/avl.c#151)*

### _deleteavl

*int _deleteavl(Avl ** tp, Avl * p, Avl * rx, int (*)(Avl *, Avl *) cmp, Avl ** del, void (*)(Avl *, void *) predel, void * arg)*

*Defined at [avl.c#169](https://github.com/Harvey-OS/harvey/blob/main/avl.c#169)*

### findpredecessor

*Avl * findpredecessor(Avl * a)*

*Defined at [avl.c#251](https://github.com/Harvey-OS/harvey/blob/main/avl.c#251)*

### findsuccessor

*Avl * findsuccessor(Avl * a)*

*Defined at [avl.c#270](https://github.com/Harvey-OS/harvey/blob/main/avl.c#270)*

### _lookupavl

*Avl * _lookupavl(Avl * t, Avl * r, int (*)(Avl *, Avl *) cmp, int neighbor)*

*Defined at [avl.c#289](https://github.com/Harvey-OS/harvey/blob/main/avl.c#289)*

### walkdel

*void walkdel(Avl * a, void * v)*

*Defined at [avl.c#324](https://github.com/Harvey-OS/harvey/blob/main/avl.c#324)*



## Enums

| enum  |

--

| UTFmax |
| Runesync |
| Runeself |
| Runeerror |
| Runemax |
| Runemask |


*Defined at [sys/include/libc.h#51](https://github.com/Harvey-OS/harvey/blob/main/sys/include/libc.h#51)*

| enum  |

--

| FmtWidth |
| FmtLeft |
| FmtPrec |
| FmtSharp |
| FmtSpace |
| FmtSign |
| FmtZero |
| FmtUnsigned |
| FmtShort |
| FmtLong |
| FmtVLong |
| FmtComma |
| FmtByte |
| FmtFlag |


*Defined at [sys/include/libc.h#136](https://github.com/Harvey-OS/harvey/blob/main/sys/include/libc.h#136)*

| enum  |

--

| PNPROC |
| PNGROUP |


*Defined at [sys/include/libc.h#293](https://github.com/Harvey-OS/harvey/blob/main/sys/include/libc.h#293)*

 one-of-a-kind

| enum  |

--

| RFNAMEG |
| RFENVG |
| RFFDG |
| RFNOTEG |
| RFPROC |
| RFMEM |
| RFNOWAIT |
| RFCNAMEG |
| RFCENVG |
| RFCFDG |
| RFREND |
| RFNOMNT |


*Defined at [sys/include/libc.h#533](https://github.com/Harvey-OS/harvey/blob/main/sys/include/libc.h#533)*

 rfork 

| enum  |

--

| StructAlign |


*Defined at [bin.c#14](https://github.com/Harvey-OS/harvey/blob/main/bin.c#14)*

| enum  |

--

| BinSize |


*Defined at [bin.c#20](https://github.com/Harvey-OS/harvey/blob/main/bin.c#20)*

| enum  |

--

| Bsize |
| Bungetsize |
| Bmagic |
| Beof |
| Bbad |
| Binactive |
| Bractive |
| Bwactive |
| Bracteof |


*Defined at [sys/include/bio.h#14](https://github.com/Harvey-OS/harvey/blob/main/sys/include/bio.h#14)*



