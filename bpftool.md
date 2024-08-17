# bpftool

# Show loaded eBPF programs
$ bpftool prog show

# Show information on specific program by name
$ bpftool prog show tamp_fs_security

# Show information on specific program by id
$ bpftool prog show id 99

# Dump bytecode
$ bpftool prog dump xlated id 99 

# Dump bytecode (C source file and linenum)
$ bpftool prog dump xlated id 99 linum

# Dump eBPF Map
$ bpftool map dump id 182

# Show tracing programs
$ bpftool perf show

## Show network packet processing programs
$ bpftool net show

# bcc-tools (/usr/share/bcc/tools)

# Show programs
$ bpflist



