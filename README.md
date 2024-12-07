# LatencyMon

Latest version: LatencyMon v 7.31


LatencyMon checks if a system running Windows is suitable for processing real-time audio and other tasks. LatencyMon analyzes the possible causes of buffer underruns by measuring kernel timer latencies and reporting DPC and ISR execution times as well as hard pagefaults. It will provide a comprehensible report and find the kernel modules and processes responsible for causing audio latencies which result in drop outs. It also provides the functionality of an ISR monitor, DPC monitor and a hard pagefault monitor.

LatencyMon will display the highest latencies of a kernel timer and report the highest execution times of ISR and DPC routines as well as hard pagefaults. In most cases it will also find the drivers and processes responsible for executing them. It will create a comprehensible report which also displays all sampled data in a detailed manner allowing you to perform in-depth analysis.
