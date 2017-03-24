

# Codesys-transfer.py, Copyright 2012 Digital Bond, Inc
# All praise to be attributed to Dale Peterson <peterson@digitalbond.com>
# All bugs and gripes to be attributed to K. Reid Wightman <krwightm@gmail.com>

Debug: connected!
>  ?
?              - show implemented commands
mem            - Memorydump
memc           - Memorydump relative to code-startaddress
memd           - Memorydump relative to data-startaddress
reflect        - reflect current command (test!)
dpt            - get data-pointer-table
ppt            - get POU-table
pid            - get project ID
pinf           - get project info
tsk            - get IEC-task-list and IEC-task-infos
tskclear       - Clear IEC task information: Cycle count, accumulated, max. and min. cycle time
startprg       - Start PLC program
stopprg        - Stop PLC program
resetprg       - Reset PLC program
resetprgcold   - Reset PLC program cold
resetprgorg    - Reset PLC program original
reload         - Reload boot project
getprgprop     - Program properties
getprgstat     - Program status
filecopy       - Copy files [from] [to]
filerename     - Rename files [old] [new]
filedelete     - Delete file [filename]
filedir        - Directory list [start directory]
saveretain     - save retains in file [filename]
restoreretain  - restore retains from file [filename]
setpwd         - set online access password
delpwd         - delete online access password
plcload        - plc load of scheduler, IEC-tasks and communication
plcloadstart   - start plc load measuring
plcloadstop    - stop plc load measuring
rtsinfo        - runtime system information (version, IO drivers)
disabledhook   - list of all hooks disabled in the RTS
------------------------------------------------------------------------
inputshow      - Input Configuration of all tasks
outputshow     - Output Configuration of all tasks
wdgshow        - Watchdog Configuration of all tasks
------------------------------------------------------------------------
canshow        - CAN info
canshowReset   - Reset CAN info counters
sysinfo        - System info
------------------------------------------------------------------------
