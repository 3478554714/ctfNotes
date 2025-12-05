## Pwndbg命令

awatch -- Set an access watchpoint for EXPRESSION.
break, brea, bre, br, b -- Set breakpoint at specified location.
break-range -- Set a breakpoint for an address range.
catch -- Set catchpoints to catch events.
catch assert -- Catch failed Ada assertions, when raised.
catch catch -- Catch an exception, when caught.
catch exception -- Catch Ada exceptions, when raised.
catch exec -- Catch calls to exec.
catch fork -- Catch calls to fork.
catch handlers -- Catch Ada exceptions, when handled.
catch load -- Catch loads of shared libraries.
catch rethrow -- Catch an exception, when rethrown.
catch signal -- Catch signals by their names and/or numbers.
catch syscall -- Catch system calls by their names, groups and/or numbers.
catch throw -- Catch an exception, when thrown.
catch unload -- Catch unloads of shared libraries.
catch vfork -- Catch calls to vfork.
clear, cl -- Clear breakpoint at specified location.
commands -- Set commands to be executed when the given breakpoints are hit.
condition -- Specify breakpoint number N to break only if COND is true.
delete, del, d -- Delete all or some breakpoints.
delete bookmark -- Delete a bookmark from the bookmark list.
delete breakpoints -- Delete all or some breakpoints or auto-display expressions.
delete checkpoint -- Delete a checkpoint (experimental).
delete display -- Cancel some expressions to be displayed when program stops.
delete mem -- Delete memory region.
delete tracepoints, delete tr -- Delete specified tracepoints.
delete tvariable -- Delete one or more trace state variables.
disable, disa, dis -- Disable all or some breakpoints.
disable breakpoints -- Disable all or some breakpoints.
disable display -- Disable some expressions to be displayed when program stops.
disable frame-filter -- GDB command to disable the specified frame-filter.
disable mem -- Disable memory region.
disable missing-debug-handler -- GDB command to disable missing debug handlers.
disable pretty-printer -- GDB command to disable the specified pretty-printer.
disable probes -- Disable probes.
disable type-printer -- GDB command to disable the specified type-printer.
disable unwinder -- GDB command to disable the specified unwinder.
disable xmethod -- GDB command to disable a specified (group of) xmethod(s).
dprintf -- Set a dynamic printf at specified location.
enable, en -- Enable all or some breakpoints.
enable breakpoints -- Enable all or some breakpoints.
enable breakpoints count -- Enable some breakpoints for COUNT hits.
enable breakpoints delete -- Enable some breakpoints and delete when hit.
enable breakpoints once -- Enable some breakpoints for one hit.
enable count -- Enable some breakpoints for COUNT hits.
enable delete -- Enable some breakpoints and delete when hit.
enable display -- Enable some expressions to be displayed when program stops.
enable frame-filter -- GDB command to enable the specified frame-filter.
enable mem -- Enable memory region.
enable missing-debug-handler -- GDB command to enable missing debug handlers.
enable once -- Enable some breakpoints for one hit.
enable pretty-printer -- GDB command to enable the specified pretty-printer.
enable probes -- Enable probes.
enable type-printer -- GDB command to enable the specified type printer.
enable unwinder -- GDB command to enable unwinders.
enable xmethod -- GDB command to enable a specified (group of) xmethod(s).
ftrace -- Set a fast tracepoint at specified location.
hbreak -- Set a hardware assisted breakpoint.
rbreak -- Set a breakpoint for all functions matching REGEXP.
rwatch -- Set a read watchpoint for EXPRESSION.
save -- Save breakpoint definitions as a script.
save breakpoints -- Save current breakpoint definitions as a script.
save gdb-index -- Save a gdb-index file.
save tracepoints -- Save current tracepoint definitions as a script.
skip -- Ignore a function while stepping.
skip delete -- Delete skip entries.
skip disable -- Disable skip entries.
skip enable -- Enable skip entries.
skip file -- Ignore a file while stepping.
skip function -- Ignore a function while stepping.
strace -- Set a static tracepoint at location or marker.
tbreak -- Set a temporary breakpoint.
tcatch -- Set temporary catchpoints to catch events.
tcatch assert -- Catch failed Ada assertions, when raised.
tcatch catch -- Catch an exception, when caught.
tcatch exception -- Catch Ada exceptions, when raised.
tcatch exec -- Catch calls to exec.
tcatch fork -- Catch calls to fork.
tcatch handlers -- Catch Ada exceptions, when handled.
tcatch load -- Catch loads of shared libraries.
tcatch rethrow -- Catch an exception, when rethrown.
tcatch signal -- Catch signals by their names and/or numbers.
tcatch syscall -- Catch system calls by their names, groups and/or numbers.
tcatch throw -- Catch an exception, when thrown.
tcatch unload -- Catch unloads of shared libraries.
tcatch vfork -- Catch calls to vfork.
thbreak -- Set a temporary hardware assisted breakpoint.
trace, trac, tra, tr, tp -- Set a tracepoint at specified location.
watch -- Set a watchpoint for EXPRESSION.

Command class: data

agent-printf -- Target agent only formatted printing, like the C "printf" function.
append -- Append target code/data to a local file.
append binary -- Append target code/data to a raw binary file.
append binary memory -- Append contents of memory to a raw binary file.
append binary value -- Append the value of an expression to a raw binary file.
append memory -- Append contents of memory to a raw binary file.
append value -- Append the value of an expression to a raw binary file.
call -- Call a function in the program.
disassemble -- Disassemble a specified section of memory.
display -- Print value of expression EXP each time the program stops.
dump -- Dump target code/data to a local file.
dump binary -- Write target code/data to a raw binary file.
dump binary memory -- Write contents of memory to a raw binary file.
dump binary value -- Write the value of an expression to a raw binary file.
dump ihex -- Write target code/data to an intel hex file.
dump ihex memory -- Write contents of memory to an ihex file.
dump ihex value -- Write the value of an expression to an ihex file.
dump memory -- Write contents of memory to a raw binary file.
dump srec -- Write target code/data to an srec file.
dump srec memory -- Write contents of memory to an srec file.
dump srec value -- Write the value of an expression to an srec file.
dump tekhex -- Write target code/data to a tekhex file.
dump tekhex memory -- Write contents of memory to a tekhex file.
dump tekhex value -- Write the value of an expression to a tekhex file.
dump value -- Write the value of an expression to a raw binary file.
dump verilog -- Write target code/data to a verilog hex file.
dump verilog memory -- Write contents of memory to a verilog hex file.
dump verilog value -- Write the value of an expression to a verilog hex file.
explore -- Explore a value or a type valid in the current context.
explore type -- Explore a type or the type of an expression.
explore value -- Explore value of an expression valid in the current context.
find -- Search memory for a sequence of bytes.
init-if-undefined -- Initialize a convenience variable if necessary.
mem -- Define attributes for memory region or reset memory region handling to target-based.
memory-tag -- Generic command for printing and manipulating memory tag properties.
memory-tag check -- Validate a pointer's logical tag against the allocation tag.
memory-tag print-allocation-tag -- Print the allocation tag for ADDRESS.
memory-tag print-logical-tag -- Print the logical tag from POINTER.
memory-tag set-allocation-tag -- Set the allocation tag(s) for a memory range.
memory-tag with-logical-tag -- Print a POINTER with a specific logical TAG.
output -- Like "print" but don't put in value history and don't print newline.
print, inspect, p -- Print value of expression EXP.
print-object, po -- Ask an Objective-C object to print itself.
printf -- Formatted printing, like the C "printf" function.
ptype -- Print definition of type TYPE.
restore -- Restore the contents of FILE to target memory.
set -- Evaluate expression EXP and assign result to variable VAR.
set ada -- Prefix command for changing Ada-specific settings.
set ada print-signatures -- Enable or disable the output of formal and return types for functions in the overloads selection menu.
set ada source-charset -- Set the Ada source character set.
set ada trust-PAD-over-XVS -- Enable or disable an optimization trusting PAD types over XVS types.
set agent -- Set debugger's willingness to use agent as a helper.
set ai-anthropic-api-key -- Set Anthropic API key.
set ai-history-size -- Set maximum number of questions and answers to keep in the prompt.
set ai-max-tokens -- Set the maximum number of tokens to return in the response.
set ai-model -- Set the name of the large language model to query.
set ai-ollama-endpoint -- Set Ollama API endpoint.
set ai-openai-api-key -- Set OpenAI API key.
set ai-show-usage -- Set whether to show how many tokens are used with each OpenAI API call.
set ai-stack-depth -- Set rows of stack context to include in the prompt for the ai command.
set ai-temperature -- Set the temperature specification for the LLM query.
set always-read-ctf -- Set whether CTF is always read.
set annotate -- Set annotation_level.
set architecture, set processor -- Set architecture of target.
set args -- Set argument list to give program being debugged when it is started.
set attachp-resolution-method -- Set how to determine the process to attach when multiple candidates exists.
set auto-connect-native-target -- Set whether GDB may automatically connect to the native target.
set auto-explore-auxv -- Set stack exploration for AUXV information; it may be really slow.
set auto-explore-pages -- Set whether to try to infer page permissions when memory maps are missing.
set auto-explore-stack -- Set stack exploration; it may be really slow.
set auto-load -- Auto-loading specific settings.
set auto-load gdb-scripts -- Enable or disable auto-loading of canned sequences of commands scripts.
set auto-load libthread-db -- Enable or disable auto-loading of inferior specific libthread_db.
set auto-load local-gdbinit -- Enable or disable auto-loading of .gdbinit script in current directory.
set auto-load python-scripts -- Set the debugger's behaviour regarding auto-loaded Python scripts.
set auto-load safe-path -- Set the list of files and directories that are safe for auto-loading.
set auto-load scripts-directory -- Set the list of directories from which to load auto-loaded scripts.
set auto-save-search -- Set automatically pass --save to "search" command.
set auto-solib-add -- Set autoloading of shared library symbols.
set backtrace -- Set backtrace specific variables.
set backtrace limit -- Set an upper bound on the number of backtrace levels.
set backtrace past-entry -- Set whether backtraces should continue past the entry point of a program.
set backtrace past-main -- Set whether backtraces should continue past "main".
set backtrace-address-color -- Set color for backtrace (address).
set backtrace-frame-label -- Set frame number label for backtrace.
set backtrace-frame-label-color -- Set color for backtrace (frame label).
set backtrace-prefix -- Set prefix for current backtrace label.
set backtrace-prefix-color -- Set color for prefix of current backtrace label.
set backtrace-symbol-color -- Set color for backtrace (symbol).
set banner-color -- Set color for banner line.
set banner-separator -- Set repeated banner separator character.
set banner-title-color -- Set color for banner title.
set banner-title-position -- Set banner title position.
set banner-title-surrounding-left -- Set banner title surrounding char (left side).
set banner-title-surrounding-right -- Set banner title surrounding char (right side).
set basenames-may-differ -- Set whether a source file may have multiple base names.
set bn-autosync -- Set whether to automatically run bn-sync every step.
set bn-decomp-style -- Set decompilation highlight theme for Binary Ninja.
set bn-il-level -- Set the IL level to use when displaying Binary Ninja decompilation.
set bn-rpc-host -- Set Binary Ninja XML-RPC server host.
set bn-rpc-port -- Set Binary Ninja XML-RPC server port.
set bn-timeout -- Set time to wait for Binary Ninja XML-RPC, in seconds.
set breakpoint -- Breakpoint specific settings.
set breakpoint always-inserted -- Set mode for inserting breakpoints.
set breakpoint auto-hw -- Set automatic usage of hardware breakpoints.
set breakpoint condition-evaluation -- Set mode of breakpoint condition evaluation.
set breakpoint pending -- Set debugger's behavior regarding pending breakpoints.
set can-use-hw-watchpoints -- Set debugger's willingness to use watchpoint hardware.
set case-sensitive -- Set case sensitivity in name search (on/off/auto).
set chain-arrow-color -- Set color of chain formatting (arrow).
set chain-arrow-left -- Set left arrow of chain formatting.
set chain-arrow-right -- Set right arrow of chain formatting.
set chain-contiguous-marker -- Set contiguous marker of chain formatting.
set chain-contiguous-marker-color -- Set color of chain formatting (contiguous marker).
set charset -- Set the host and target character sets.
set check, set ch, set c -- Set the status of the type/range checker.
set check range -- Set range checking (on/warn/off/auto).
set check type -- Set strict type checking.
set circular-trace-buffer -- Set target's use of circular trace buffer.
set code-cache -- Set cache use for code segment access.
set code-prefix -- Set prefix marker for 'context code' command.
set code-prefix-color -- Set color for 'context code' command (prefix marker).
set coerce-float-to-double -- Set coercion of floats to doubles when calling functions.
set comment-color -- Set color for comment.
set compile-args -- Set compile command GCC command-line arguments.
set compile-gcc -- Set compile command GCC driver filename.
set complaints -- Set max number of complaints about incorrect symbols.
set confirm -- Set whether to confirm potentially dangerous operations.
set context-backtrace-lines -- Set number of lines to print in the backtrace context.
set context-clear-screen -- Set whether to clear the screen before printing the context.
set context-code-lines -- Set number of source code lines to print by the context command.
set context-code-tabstop -- Set number of spaces that a <tab> in the source code counts for.
set context-disasm-lines -- Set number of additional lines to print in the disasm context.
set context-flag-bracket-color -- Set color for flags register (bracket).
set context-flag-changed-color -- Set color for flags register (flag changed).
set context-flag-set-color -- Set color for flags register (flag set).
set context-flag-unset-color -- Set color for flags register (flag unset).
set context-flag-value-color -- Set color for flags register (register value).
set context-ghidra -- Set when to try to decompile the current function with ghidra.
set context-history-size -- Set number of context history entries to store.
set context-integration-decompile -- Set whether context should fall back to decompilation with no source code.
set context-max-threads -- Set maximum number of threads displayed by the context command.
set context-output -- Set where Pwndbg should output ("stdout" or file/tty).
set context-register-changed-color -- Set color for registers label (change marker).
set context-register-changed-marker -- Set change marker for registers label.
set context-register-color -- Set color for registers label.
set context-reserve-lines -- Set when to reserve lines after the prompt to reduce context shake.
set context-sections -- Set which context sections are displayed (controls order).
set context-stack-lines -- Set number of lines to print in the stack context.
set cp-abi -- Set the ABI used for inspecting C++ objects.
set cwd -- Set the current working directory to be used when the inferior is started.
set cymbol-editor -- Set path to the editor for editing custom structures.
set data-directory -- Set GDB's data directory.
set dcache -- Use this command to set number of lines in dcache and line-size.
set dcache line-size -- Set dcache line size in bytes (must be power of 2).
set dcache size -- Set number of dcache lines.
set debug -- Generic command for setting gdb debugging flags.
set debug arch -- Set architecture debugging.
set debug auto-load -- Set auto-load verifications debugging.
set debug bfd-cache -- Set bfd cache debugging.
set debug breakpoint -- Set breakpoint location debugging.
set debug check-physname -- Set cross-checking of "physname" code against demangler.
set debug coff-pe-read -- Set coff PE read debugging.
set debug compile -- Set compile command debugging.
set debug compile-cplus-scopes -- Set debugging of C++ compile scopes.
set debug compile-cplus-types -- Set debugging of C++ compile type conversion.
set debug displaced -- Set displaced stepping debugging.
set debug dwarf-die -- Set debugging of the DWARF DIE reader.
set debug dwarf-line -- Set debugging of the dwarf line reader.
set debug dwarf-read -- Set debugging of the DWARF reader.
set debug entry-values -- Set entry values and tail call frames debugging.
set debug event-loop -- Set event-loop debugging.
set debug expression -- Set expression debugging.
set debug fortran-array-slicing -- Set debugging of Fortran array slicing.
set debug frame -- Set frame debugging.
set debug index-cache -- Set display of index-cache debug messages.
set debug infcall -- Set inferior call debugging.
set debug infrun -- Set inferior debugging.
set debug jit -- Set JIT debugging.
set debug libthread-db -- Set libthread-db debugging.
set debug linux-namespaces -- Set debugging of GNU/Linux namespaces module.
set debug linux-nat -- Set debugging of GNU/Linux native target.
set debug notification -- Set debugging of async remote notification.
set debug observer -- Set observer debugging.
set debug overload -- Set debugging of C++ overloading.
set debug parser -- Set parser debugging.
set debug py-breakpoint -- Set Python breakpoint debugging.
set debug py-micmd -- Set Python micmd debugging.
set debug py-unwind -- Set Python unwinder debugging.
set debug record -- Set debugging of record/replay feature.
set debug remote -- Set debugging of remote protocol.
set debug remote-packet-max-chars -- Set the maximum number of characters to display for each remote packet.
set debug separate-debug-file -- Set printing of separate debug info file search debug.
set debug serial -- Set serial debugging.
set debug skip -- Set whether to print the debug output about skipping files and functions.
set debug solib -- Set solib debugging.
set debug stap-expression -- Set SystemTap expression debugging.
set debug symbol-lookup -- Set debugging of symbol lookup.
set debug symfile -- Set debugging of the symfile functions.
set debug symtab-create -- Set debugging of symbol table creation.
set debug target -- Set target debugging.
set debug threads -- Set thread debugging.
set debug timestamp -- Set timestamping of debugging messages.
set debug tui -- Set tui debugging.
set debug varobj -- Set varobj debugging.
set debug xml -- Set XML parser debugging.
set debug-events -- Set display internal event debugging info.
set debug-file-directory -- Set the directories where separate debug symbols are searched for.
set debuginfod -- Set debuginfod options.
set debuginfod enabled -- Set whether to use debuginfod.
set debuginfod urls -- Set the list of debuginfod server URLs.
set debuginfod verbose -- Set verbosity of debuginfod output.
set decompiler -- Set framework that your ghidra plugin installed.
set default-collect -- Set the list of expressions to collect by default.
set default-visualize-chunk-number -- Set default number of chunks to visualize.
set demangle-style -- Set the current C++ demangling style.
set dereference-limit -- Set max number of pointers to dereference in a chain.
set detach-on-fork -- Set whether gdb will detach the child of a fork.
set direct-call-timeout -- Set the timeout, for direct calls to inferior function calls.
set directories -- Set the search path for finding source files.
set disable-colors -- Set whether to color the output or not.
set disable-randomization -- Set disabling of debuggee's virtual address space randomization.
set disasm-annotations -- Set display annotations for instructions.
set disasm-branch-color -- Set color for disasm (branch/call instruction).
set disasm-branch-off -- Set marker for branches that will NOT be taken.
set disasm-branch-on -- Set marker for branches that WILL be taken.
set disasm-inline-symbols -- Set replacing constant operands with their symbol in the disassembly.
set disasm-reg-alias -- Set force the disassembly to use register aliases (e.g. aarch64 x29 -> fp).
set disasm-telescope-depth -- Set depth of telescope for disasm annotations.
set disasm-telescope-string-length -- Set the number of characters in strings to display in disasm annotations.
set disassemble-next-line -- Set whether to disassemble next source line or insn when execution stops.
set disassembler-options -- Set the disassembler options.
set disassembly-flavor -- Set the disassembly flavor.
set disconnected-dprintf -- Set whether dprintf continues after GDB disconnects.
set disconnected-tracing -- Set whether tracing continues after GDB disconnects.
set displaced-stepping -- Set debugger's willingness to use displaced stepping.
set dprintf-channel -- Set the channel to use for dynamic printf.
set dprintf-function -- Set the function to use for dynamic printf.
set dprintf-style -- Set the style of usage for dynamic printf.
set dump-excluded-mappings -- Set whether gcore should dump mappings marked with the VM_DONTDUMP flag.
set editing -- Set editing of command lines as they are typed.
set emulate -- Set unicorn emulation of code from the current PC register.
set emulate-annotations -- Set unicorn emulation for instruction annotations.
set emulate-future-annotations -- Set unicorn emulation for future instruction's annotations.
set endian -- Set endianness of target.
set enhance-comment-color -- Set color of value enhance (comment).
set enhance-integer-value-color -- Set color of value enhance (integer).
set enhance-string-value-color -- Set color of value enhance (string).
set enhance-unknown-color -- Set color of value enhance (unknown value).
set environment -- Set environment variable value to give the program.
set exception-debugger -- Set whether to debug exceptions raised in Pwndbg commands.
set exception-verbose -- Set print a full stacktrace for exceptions raised in Pwndbg commands.
set exec-direction -- Set direction of execution.
set exec-done-display -- Set notification of completion for asynchronous execution commands.
set exec-file-mismatch -- Set exec-file-mismatch handling (ask|warn|off).
set exec-wrapper -- Set a wrapper for running programs.
set extended-prompt -- Set the extended prompt.
set extension-language -- Set mapping between filename extension and source language.
set filename-display -- Set how to display filenames.
set follow-exec-mode -- Set debugger response to a program call of exec.
set follow-fork-mode -- Set debugger response to a program call of fork or vfork.
set fortran -- Prefix command for changing Fortran-specific settings.
set fortran repack-array-slices -- Enable or disable repacking of non-contiguous array slices.
set frame-filter -- Prefix command for 'set' frame-filter related operations.
set frame-filter priority -- GDB command to set the priority of the specified frame-filter.
set gcc-compiler-path -- Set path to the gcc/g++ toolchain for generating imported symbols.
set gdb-workaround-stop-event -- Set asynchronous stop events to improve 'commands' functionality.
set glibc -- Set glibc version for heap heuristics resolution (e.g. 2.31).
set global-max-fast -- Set the address of global_max_fast.
set gnutarget, set g -- Set the current BFD target.
set go-dump-debug -- Set color for 'go-dump' command's debug info when --debug is specified.
set go-dump-indent-amount -- Set the indent amount for go-dump pretty printing.
set go-dump-line-width -- Set the soft line width for go-dump pretty printing.
set guile, set gu -- Prefix command for Guile preference settings.
set guile print-stack -- Set mode for Guile exception printing on error.
set heap-corruption-check-limit -- Set amount of chunks to traverse for the bin corruption check.
set heap-dereference-limit -- Set number of chunks to dereference in each bin.
set height -- Set number of lines in a page for GDB output pagination.
set hexdump-address-color -- Set color for hexdump command (address label).
set hexdump-ascii-block-separator -- Set block separator char of the hexdump command.
set hexdump-byte-separator -- Set separator of single bytes in hexdump (does NOT affect group separator).
set hexdump-bytes -- Set number of bytes printed by hexdump command.
set hexdump-colorize-ascii -- Set whether to colorize the hexdump command ascii section.
set hexdump-group-use-big-endian -- Set use big-endian within each group of bytes in hexdump command.
set hexdump-group-width -- Set number of bytes grouped in hexdump command.
set hexdump-highlight-group-lsb -- Set highlight LSB of each group.
set hexdump-limit-mb -- Set the maximum size in megabytes (MB) `hexdump` will read.
set hexdump-normal-color -- Set color for hexdump command (normal bytes).
set hexdump-offset-color -- Set color for hexdump command (offset label).
set hexdump-printable-color -- Set color for hexdump command (printable characters).
set hexdump-separator-color -- Set color for hexdump command (group separator).
set hexdump-special-color -- Set color for hexdump command (special bytes).
set hexdump-width -- Set line width of hexdump command.
set hexdump-zero-color -- Set color for hexdump command (zero bytes).
set highlight-breakpoints -- Set whether to highlight breakpoints.
set highlight-color -- Set color added to highlights like source/pc.
set highlight-pc -- Set whether to highlight the current instruction.
set highlight-source -- Set whether to highlight the closest source line.
set history -- Generic command for setting command history parameters.
set history expansion -- Set history expansion on command input.
set history filename -- Set the filename in which to record the command history.
set history remove-duplicates -- Set how far back in history to look for and remove duplicate entries.
set history save -- Set saving of the history record on exit.
set history size -- Set the size of the command history.
set host-charset -- Set the host character set.
set ida-rpc-host -- Set ida xmlrpc server address.
set ida-rpc-port -- Set ida xmlrpc server port.
set ida-timeout -- Set time to wait for ida xmlrpc in seconds.
set index-cache -- Set index-cache options.
set index-cache directory -- Set the directory of the index cache.
set index-cache enabled -- Enable the index cache.
set indirect-call-timeout -- Set the timeout, for indirect calls to inferior function calls.
set inferior-tty, tty -- Set terminal for future runs of program being debugged.
set input-radix -- Set default input radix for entering numbers.
set integration-function-lookup -- Set use integration to look up function type signatures.
set integration-provider -- Set which provider to use for integration features.
set integration-smart-enhance -- Set use integration to determine when to disassemble during enhancing.
set integration-symbol-lookup -- Set whether to use integration to look up unknown symbols.
set interactive-mode -- Set whether GDB's standard input is a terminal.
set kernel-vmmap -- Set the method to get vmmap information when debugging via QEMU kernel.
set language -- Set the current source language.
set left-pad-disasm -- Set whether to left-pad disassembly.
set libthread-db-search-path -- Set search path for libthread_db.
set listsize -- Set number of source lines gdb will list by default.
set logging -- Set logging options.
set logging debugredirect -- Set the logging debug output mode.
set logging enabled -- Enable logging.
set logging file -- Set the current logfile.
set logging overwrite -- Set whether logging overwrites or appends to the log file.
set logging redirect -- Set the logging output mode.
set main-arena -- Set the address of main_arena.
set max-completions -- Set maximum number of completion candidates.
set max-decimal-number -- Set show all numbers greater than this in hex.
set max-user-call-depth -- Set the max call depth for non-python/scheme user-defined commands.
set max-value-size -- Set maximum sized value gdb will load from the inferior.
set max-visualize-chunk-size -- Set max display size for heap chunks visualization (0 for display all).
set may-call-functions -- Set permission to call functions in the program.
set may-insert-breakpoints -- Set permission to insert breakpoints in the target.
set may-insert-fast-tracepoints -- Set permission to insert fast tracepoints in the target.
set may-insert-tracepoints -- Set permission to insert tracepoints in the target.
set may-interrupt -- Set permission to interrupt or signal the target.
set may-write-memory -- Set permission to write into target memory.
set may-write-registers -- Set permission to write into registers.
set mem -- Memory regions settings.
set mem inaccessible-by-default -- Set handling of unknown memory regions.
set memory-code-color -- Set color for executable memory.
set memory-data-color -- Set color for all other writable memory.
set memory-guard-color -- Set color added to all guard pages (no perms).
set memory-heap-color -- Set color for heap memory.
set memory-rodata-color -- Set color for all read only memory.
set memory-stack-color -- Set color for stack memory.
set memory-wx-color -- Set color added to all WX memory.
set message-breakpoint-color -- Set color of breakpoint messages.
set message-debug-color -- Set color of debug messages.
set message-error-color -- Set color of error messages.
set message-exit-color -- Set color of exit messages.
set message-hint-color -- Set color of hint and marker messages.
set message-info-color -- Set color of info messages.
set message-notice-color -- Set color of notice messages.
set message-signal-color -- Set color of signal messages.
set message-status-off-color -- Set color of off status messages.
set message-status-on-color -- Set color of on status messages.
set message-success-color -- Set color of success messages.
set message-system-color -- Set color of system messages.
set message-warning-color -- Set color of warning messages.
set mi-async -- Set whether MI asynchronous mode is enabled.
set mp -- Set the address of mp_.
set mpx -- Set Intel Memory Protection Extensions specific variables.
set multiple-symbols -- Set how the debugger handles ambiguities in expressions.
set nearpc-address-color -- Set color for nearpc command (address).
set nearpc-argument-color -- Set color for nearpc command (target argument).
set nearpc-backwards-lines -- Set number of lines before the pc to print for the nearpc command.
set nearpc-branch-marker -- Set branch marker line for nearpc command.
set nearpc-branch-marker-color -- Set color for nearpc command (branch marker line).
set nearpc-branch-marker-contiguous -- Set contiguous branch marker line for nearpc command.
set nearpc-breakpoint-color -- Set color for nearpc command (breakpoint marker).
set nearpc-breakpoint-prefix -- Set breakpoint marker for nearpc command.
set nearpc-integration-comments -- Set whether to show comments from integration provider.
set nearpc-integration-comments-color -- Set color for nearpc command (integration comments).
set nearpc-lines -- Set number of lines to print for the nearpc command.
set nearpc-num-opcode-bytes -- Set number of opcode bytes to print for each instruction.
set nearpc-opcode-separator-bytes -- Set number of spaces between opcode bytes.
set nearpc-prefix -- Set prefix marker for nearpc command.
set nearpc-prefix-color -- Set color for nearpc command (prefix marker).
set nearpc-show-args -- Set whether to show call arguments below instruction.
set nearpc-symbol-color -- Set color for nearpc command (symbol).
set nearpc-syscall-name-color -- Set color for nearpc command (resolved syscall name).
set ng-search-on-fail -- Set let the ng-slot* commands search the heap if necessary.
set ng-vis-count -- Set default count for ng-vis.
set non-stop -- Set whether gdb controls the inferior in non-stop mode.
set objc-max-function-arguments -- Set maximum number of arguments to resolve for an Objective-C method call.
set objc-max-function-types-depth -- Set maximum allowed depth for a type in an Objective-C method call.
set observer -- Set whether gdb controls the inferior in observer mode.
set opaque-type-resolution -- Set resolution of opaque struct/class/union types (if set before loading symbols).
set osabi -- Set OS ABI of target.
set output-radix -- Set default output radix for printing of values.
set overload-resolution -- Set overload resolution in evaluating C++ functions.
set pagination -- Set state of GDB output pagination.
set print, set pr, set p -- Generic command for setting how things print.
set print address -- Set printing of addresses.
set print array -- Set pretty formatting of arrays.
set print array-indexes -- Set printing of array indexes.
set print asm-demangle -- Set demangling of C++/ObjC names in disassembly listings.
set print characters -- Set limit on string chars to print.
set print demangle -- Set demangling of encoded C++/ObjC names when displaying symbols.
set print elements -- Set limit on array elements to print.
set print entry-values -- Set printing of function arguments at function entry.
set print finish -- Set whether `finish' prints the return value.
set print frame-arguments -- Set printing of non-scalar frame arguments.
set print frame-info -- Set printing of frame information.
set print inferior-events -- Set printing of inferior events (such as inferior start and exit).
set print max-depth -- Set maximum print depth for nested structures, unions and arrays.
set print max-symbolic-offset -- Set the largest offset that will be printed in <SYMBOL+1234> form.
set print memory-tag-violations -- Set printing of memory tag violations for pointers.
set print nibbles -- Set whether to print binary values in groups of four bits.
set print null-stop -- Set printing of char arrays to stop at first null char.
set print object -- Set printing of C++ virtual function tables.
set print pascal_static-members -- Set printing of pascal static members.
set print pretty -- Set pretty formatting of structures.
set print raw-frame-arguments -- Set whether to print frame arguments in raw form.
set print raw-values -- Set whether to print values in raw form.
set print repeats -- Set threshold for repeated print elements.
set print sevenbit-strings -- Set printing of 8-bit characters in strings as \nnn.
set print static-members -- Set printing of C++ static members.
set print symbol -- Set printing of symbol names when printing pointers.
set print symbol-filename -- Set printing of source filename and line number with <SYMBOL>.
set print symbol-loading -- Set printing of symbol loading messages.
set print thread-events -- Set printing of thread events (such as thread start and exit).
set print type -- Generic command for showing type-printing settings.
set print type hex -- Set printing of struct members sizes and offsets using hex notation.
set print type methods -- Set printing of methods defined in classes.
set print type nested-type-limit -- Set the number of recursive nested type definitions to print ("unlimited" or -1 to show all).
set print type typedefs -- Set printing of typedefs defined in classes.
set print union -- Set printing of unions interior to structures.
set print vtbl -- Set printing of C++ virtual function tables.
set prompt -- Set gdb's prompt.
set prompt-alive-color -- Set prompt alive color.
set prompt-color -- Set prompt color.
set prop-name-color -- Set color used to highlight the name in name-value pairs.
set prop-title-color -- Set color used to highlight the title of name-value pair groups.
set prop-value-color -- Set color used to highlight the value in name-value pairs.
set python -- Prefix command for python preference settings.
set python dont-write-bytecode -- Set whether the Python interpreter should avoid byte-compiling python modules.
set python ignore-environment -- Set whether the Python interpreter should ignore environment variables.
set python print-stack -- Set mode for Python stack dump on error.
set radix -- Set default input and output number radices.
set range-stepping -- Enable or disable range stepping.
set ravenscar -- Prefix command for changing Ravenscar-specific settings.
set ravenscar task-switching -- Enable or disable support for GNAT Ravenscar tasks.
set record, set rec -- Set record options.
set record btrace -- Set record options.
set record btrace bts -- Set record btrace bts options.
set record btrace bts buffer-size -- Set the record/replay bts buffer size.
set record btrace cpu -- Set the cpu to be used for trace decode.
set record btrace cpu auto -- Automatically determine the cpu to be used for trace decode.
set record btrace cpu none -- Do not enable errata workarounds for trace decode.
set record btrace pt -- Set record btrace pt options.
set record btrace pt buffer-size -- Set the record/replay pt buffer size.
set record btrace replay-memory-access -- Set what memory accesses are allowed during replay.
set record full -- Set record options.
set record full insn-number-max -- Set record/replay buffer limit.
set record full memory-query -- Set whether query if PREC cannot record memory change of next instruction.
set record full stop-at-limit -- Set whether record/replay stops when record/replay buffer becomes full.
set record function-call-history-size -- Set number of function to print in "record function-call-history".
set record instruction-history-size -- Set number of instructions to print in "record instruction-history".
set remote -- Remote protocol specific variables.
set remote TracepointSource-packet -- Set use of remote protocol `TracepointSource' (TracepointSource) packet.
set remote Z-packet -- Set use of remote protocol `Z' packets.
set remote access-watchpoint-packet -- Set use of remote protocol `Z4' (access-watchpoint) packet.
set remote agent-packet -- Set use of remote protocol `QAgent' (agent) packet.
set remote allow-packet -- Set use of remote protocol `QAllow' (allow) packet.
set remote attach-packet -- Set use of remote protocol `vAttach' (attach) packet.
set remote binary-download-packet, 
   set remote X-packet -- Set use of remote protocol `X' (binary-download) packet.
set remote breakpoint-commands-packet -- Set use of remote protocol `BreakpointCommands' (breakpoint-commands) packet.
set remote btrace-conf-bts-size-packet -- Set use of remote protocol `Qbtrace-conf:bts:size' (btrace-conf-bts-size) packet.
set remote btrace-conf-pt-size-packet -- Set use of remote protocol `Qbtrace-conf:pt:size' (btrace-conf-pt-size) packet.
set remote catch-syscalls-packet -- Set use of remote protocol `QCatchSyscalls' (catch-syscalls) packet.
set remote conditional-breakpoints-packet -- Set use of remote protocol `ConditionalBreakpoints' (conditional-breakpoints) packet.
set remote conditional-tracepoints-packet -- Set use of remote protocol `ConditionalTracepoints' (conditional-tracepoints) packet.
set remote ctrl-c-packet -- Set use of remote protocol `vCtrlC' (ctrl-c) packet.
set remote disable-btrace-packet -- Set use of remote protocol `Qbtrace:off' (disable-btrace) packet.
set remote disable-randomization-packet -- Set use of remote protocol `QDisableRandomization' (disable-randomization) packet.
set remote enable-btrace-bts-packet -- Set use of remote protocol `Qbtrace:bts' (enable-btrace-bts) packet.
set remote enable-btrace-pt-packet -- Set use of remote protocol `Qbtrace:pt' (enable-btrace-pt) packet.
set remote environment-hex-encoded-packet -- Set use of remote protocol `QEnvironmentHexEncoded' (environment-hex-encoded) packet.
set remote environment-reset-packet -- Set use of remote protocol `QEnvironmentReset' (environment-reset) packet.
set remote environment-unset-packet -- Set use of remote protocol `QEnvironmentUnset' (environment-unset) packet.
set remote exec-event-feature-packet -- Set use of remote protocol `exec-event-feature' (exec-event-feature) packet.
set remote exec-file -- Set the remote pathname for "run".
set remote fast-tracepoints-packet -- Set use of remote protocol `FastTracepoints' (fast-tracepoints) packet.
set remote fetch-register-packet, 
   set remote p-packet -- Set use of remote protocol `p' (fetch-register) packet.
set remote fork-event-feature-packet -- Set use of remote protocol `fork-event-feature' (fork-event-feature) packet.
set remote get-thread-information-block-address-packet -- Set use of remote protocol `qGetTIBAddr' (get-thread-information-block-address) packet.
set remote get-thread-local-storage-address-packet -- Set use of remote protocol `qGetTLSAddr' (get-thread-local-storage-address) packet.
set remote hardware-breakpoint-limit -- Set the maximum number of target hardware breakpoints.
set remote hardware-breakpoint-packet -- Set use of remote protocol `Z1' (hardware-breakpoint) packet.
set remote hardware-watchpoint-length-limit -- Set the maximum length (in bytes) of a target hardware watchpoint.
set remote hardware-watchpoint-limit -- Set the maximum number of target hardware watchpoints.
set remote hostio-close-packet -- Set use of remote protocol `vFile:close' (hostio-close) packet.
set remote hostio-fstat-packet -- Set use of remote protocol `vFile:fstat' (hostio-fstat) packet.
set remote hostio-open-packet -- Set use of remote protocol `vFile:open' (hostio-open) packet.
set remote hostio-pread-packet -- Set use of remote protocol `vFile:pread' (hostio-pread) packet.
set remote hostio-pwrite-packet -- Set use of remote protocol `vFile:pwrite' (hostio-pwrite) packet.
set remote hostio-readlink-packet -- Set use of remote protocol `vFile:readlink' (hostio-readlink) packet.
set remote hostio-setfs-packet -- Set use of remote protocol `vFile:setfs' (hostio-setfs) packet.
set remote hostio-unlink-packet -- Set use of remote protocol `vFile:unlink' (hostio-unlink) packet.
set remote hwbreak-feature-packet -- Set use of remote protocol `hwbreak-feature' (hwbreak-feature) packet.
set remote install-in-trace-packet -- Set use of remote protocol `InstallInTrace' (install-in-trace) packet.
set remote interrupt-on-connect -- Set whether interrupt-sequence is sent to remote target when gdb connects to.
set remote interrupt-sequence -- Set interrupt sequence to remote target.
set remote kill-packet -- Set use of remote protocol `vKill' (kill) packet.
set remote library-info-packet -- Set use of remote protocol `qXfer:libraries:read' (library-info) packet.
set remote library-info-svr4-packet -- Set use of remote protocol `qXfer:libraries-svr4:read' (library-info-svr4) packet.
set remote memory-map-packet -- Set use of remote protocol `qXfer:memory-map:read' (memory-map) packet.
set remote memory-read-packet-size -- Set the maximum number of bytes per memory-read packet.
set remote memory-tagging-feature-packet -- Set use of remote protocol `memory-tagging-feature' (memory-tagging-feature) packet.
set remote memory-write-packet-size -- Set the maximum number of bytes per memory-write packet.
set remote multiprocess-feature-packet -- Set use of remote protocol `multiprocess-feature' (multiprocess-feature) packet.
set remote no-resumed-stop-reply-packet -- Set use of remote protocol `N stop reply' (no-resumed-stop-reply) packet.
set remote noack-packet -- Set use of remote protocol `QStartNoAckMode' (noack) packet.
set remote osdata-packet -- Set use of remote protocol `qXfer:osdata:read' (osdata) packet.
set remote pass-signals-packet -- Set use of remote protocol `QPassSignals' (pass-signals) packet.
set remote pid-to-exec-file-packet -- Set use of remote protocol `qXfer:exec-file:read' (pid-to-exec-file) packet.
set remote program-signals-packet -- Set use of remote protocol `QProgramSignals' (program-signals) packet.
set remote query-attached-packet -- Set use of remote protocol `qAttached' (query-attached) packet.
set remote read-aux-vector-packet -- Set use of remote protocol `qXfer:auxv:read' (read-aux-vector) packet.
set remote read-btrace-conf-packet -- Set use of remote protocol `qXfer:btrace-conf' (read-btrace-conf) packet.
set remote read-btrace-packet -- Set use of remote protocol `qXfer:btrace' (read-btrace) packet.
set remote read-fdpic-loadmap-packet -- Set use of remote protocol `qXfer:fdpic:read' (read-fdpic-loadmap) packet.
set remote read-sdata-object-packet -- Set use of remote protocol `qXfer:statictrace:read' (read-sdata-object) packet.
set remote read-siginfo-object-packet -- Set use of remote protocol `qXfer:siginfo:read' (read-siginfo-object) packet.
set remote read-watchpoint-packet -- Set use of remote protocol `Z3' (read-watchpoint) packet.
set remote reverse-continue-packet -- Set use of remote protocol `bc' (reverse-continue) packet.
set remote reverse-step-packet -- Set use of remote protocol `bs' (reverse-step) packet.
set remote run-packet -- Set use of remote protocol `vRun' (run) packet.
set remote search-memory-packet -- Set use of remote protocol `qSearch:memory' (search-memory) packet.
set remote set-register-packet, 
   set remote P-packet -- Set use of remote protocol `P' (set-register) packet.
set remote set-working-dir-packet -- Set use of remote protocol `QSetWorkingDir' (set-working-dir) packet.
set remote software-breakpoint-packet -- Set use of remote protocol `Z0' (software-breakpoint) packet.
set remote startup-with-shell-packet -- Set use of remote protocol `QStartupWithShell' (startup-with-shell) packet.
set remote static-tracepoints-packet -- Set use of remote protocol `StaticTracepoints' (static-tracepoints) packet.
set remote supported-packets-packet -- Set use of remote protocol `qSupported' (supported-packets) packet.
set remote swbreak-feature-packet -- Set use of remote protocol `swbreak-feature' (swbreak-feature) packet.
set remote symbol-lookup-packet -- Set use of remote protocol `qSymbol' (symbol-lookup) packet.
set remote system-call-allowed -- Set if the host system(3) call is allowed for the target.
set remote target-features-packet -- Set use of remote protocol `qXfer:features:read' (target-features) packet.
set remote thread-events-packet -- Set use of remote protocol `QThreadEvents' (thread-events) packet.
set remote thread-options-packet -- Set use of remote protocol `QThreadOptions' (thread-options) packet.
set remote threads-packet -- Set use of remote protocol `qXfer:threads:read' (threads) packet.
set remote trace-buffer-size-packet -- Set use of remote protocol `QTBuffer:size' (trace-buffer-size) packet.
set remote trace-status-packet -- Set use of remote protocol `qTStatus' (trace-status) packet.
set remote traceframe-info-packet -- Set use of remote protocol `qXfer:traceframe-info:read' (traceframe-info) packet.
set remote unwind-info-block-packet -- Set use of remote protocol `qXfer:uib:read' (unwind-info-block) packet.
set remote verbose-resume-packet -- Set use of remote protocol `vCont' (verbose-resume) packet.
set remote verbose-resume-supported-packet -- Set use of remote protocol `vContSupported' (verbose-resume-supported) packet.
set remote vfork-event-feature-packet -- Set use of remote protocol `vfork-event-feature' (vfork-event-feature) packet.
set remote write-siginfo-object-packet -- Set use of remote protocol `qXfer:siginfo:write' (write-siginfo-object) packet.
set remote write-watchpoint-packet -- Set use of remote protocol `Z2' (write-watchpoint) packet.
set remoteaddresssize -- Set the maximum size of the address (in bits) in a memory packet.
set remotecache -- Set cache use for remote targets.
set remoteflow -- Set use of hardware flow control for remote serial I/O.
set remotelogbase -- Set numerical base for remote session logging.
set remotelogfile -- Set filename for remote session recording.
set remotetimeout -- Set timeout limit to wait for target to respond.
set remotewritesize -- Set the maximum number of bytes per memory write packet (deprecated).
set resolve-heap-via-heuristic -- Set the strategy to resolve heap via heuristic.
set safe-linking -- Set whether glibc uses safe-linking.
set schedule-multiple -- Set mode for resuming threads of all processes.
set scheduler-locking -- Set mode for locking scheduler during execution.
set script-extension -- Set mode for script filename extension recognition.
set serial -- Set default serial/parallel port configuration.
set serial baud -- Set baud rate for remote serial I/O.
set serial parity -- Set parity for remote serial I/O.
set show-compact-regs -- Set whether to show a compact register view with columns.
set show-compact-regs-columns -- Set the number of columns (0 for dynamic number of columns).
set show-compact-regs-min-width -- Set the minimum width of each column.
set show-compact-regs-separation -- Set the number of spaces separating columns.
set show-flags -- Set whether to show flags registers.
set show-retaddr-reg -- Set whether to show return address register.
set show-tips -- Set whether to display the tip of the day on startup.
set solib-search-path -- Set the search path for loading non-absolute shared library symbol files.
set source -- Generic command for setting how sources are handled.
set source open -- Set whether GDB should open source files.
set stack-cache -- Set cache use for stack access.
set startup-quietly -- Set whether GDB should start up quietly.
set startup-with-shell -- Set use of shell to start subprocesses.  The default is on.
set step-mode -- Set mode of the step operation.
set stop-on-solib-events -- Set stopping for shared library events.
set struct-convention -- Set the convention for returning small structs.
set style -- Style-specific settings.
set style address, set style disassembler address -- Address display styling.
set style address background -- Set the background color for this property.
set style address foreground -- Set the foreground color for this property.
set style address intensity -- Set the display intensity for this property.
set style disassembler -- Style-specific settings for the disassembler.
set style disassembler comment -- Disassembler comment display styling.
set style disassembler comment background -- Set the background color for this property.
set style disassembler comment foreground -- Set the foreground color for this property.
set style disassembler comment intensity -- Set the display intensity for this property.
set style disassembler enabled -- Set whether disassembler output styling is enabled.
set style disassembler immediate -- Disassembler immediate display styling.
set style disassembler immediate background -- Set the background color for this property.
set style disassembler immediate foreground -- Set the foreground color for this property.
set style disassembler immediate intensity -- Set the display intensity for this property.
set style disassembler mnemonic -- Disassembler mnemonic display styling.
set style disassembler mnemonic background -- Set the background color for this property.
set style disassembler mnemonic foreground -- Set the foreground color for this property.
set style disassembler mnemonic intensity -- Set the display intensity for this property.
set style disassembler register -- Disassembler register display styling.
set style disassembler register background -- Set the background color for this property.
set style disassembler register foreground -- Set the foreground color for this property.
set style disassembler register intensity -- Set the display intensity for this property.
set style enabled -- Set whether CLI styling is enabled.
set style filename -- Filename display styling.
set style filename background -- Set the background color for this property.
set style filename foreground -- Set the foreground color for this property.
set style filename intensity -- Set the display intensity for this property.
set style function, set style disassembler symbol -- Function name display styling.
set style function background -- Set the background color for this property.
set style function foreground -- Set the foreground color for this property.
set style function intensity -- Set the display intensity for this property.
set style highlight -- Highlight display styling.
set style highlight background -- Set the background color for this property.
set style highlight foreground -- Set the foreground color for this property.
set style highlight intensity -- Set the display intensity for this property.
set style metadata -- Metadata display styling.
set style metadata background -- Set the background color for this property.
set style metadata foreground -- Set the foreground color for this property.
set style metadata intensity -- Set the display intensity for this property.
set style sources -- Set whether source code styling is enabled.
set style title -- Title display styling.
set style title background -- Set the background color for this property.
set style title foreground -- Set the foreground color for this property.
set style title intensity -- Set the display intensity for this property.
set style tui-active-border -- TUI active border display styling.
set style tui-active-border background -- Set the background color for this property.
set style tui-active-border foreground -- Set the foreground color for this property.
set style tui-border -- TUI border display styling.
set style tui-border background -- Set the background color for this property.
set style tui-border foreground -- Set the foreground color for this property.
set style tui-current-position -- Set whether to style text highlighted by the TUI's current position indicator.
set style variable -- Variable name display styling.
set style variable background -- Set the background color for this property.
set style variable foreground -- Set the foreground color for this property.
set style variable intensity -- Set the display intensity for this property.
set style version -- Version string display styling.
set style version background -- Set the background color for this property.
set style version foreground -- Set the foreground color for this property.
set style version intensity -- Set the display intensity for this property.
set substitute-path -- Add a substitution rule to rewrite the source directories.
set suppress-cli-notifications -- Set whether printing notifications on CLI is suppressed.
set syntax-highlight -- Set source code / assembly syntax highlight.
set syntax-highlight-style -- Set source code / assembly syntax highlight stylename of pygments module.
set sysroot, set solib-absolute-prefix -- Set an alternate system root.
set target-charset -- Set the target character set.
set target-file-system-kind -- Set assumed file system kind for target reported file names.
set target-wide-charset -- Set the target wide character set.
set tcache -- Set the address pointed by tcache.
set tcp -- TCP protocol specific variables.
set tcp auto-retry -- Set auto-retry on socket connect.
set tcp connect-timeout -- Set timeout limit in seconds for socket connection.
set tdesc -- Set target description specific variables.
set tdesc filename -- Set the file to read for an XML target description.
set telescope-dont-skip-registers -- Set don't skip a repeated line if a registers points to it.
set telescope-frame-print-retaddr -- Set print one pointer past the stack frame.
set telescope-framepointer-offset -- Set print offset to framepointer for each address, if sufficiently small.
set telescope-lines -- Set number of lines to printed by the telescope command.
set telescope-offset-color -- Set color of the telescope command (offset prefix).
set telescope-offset-delimiter -- Set offset delimiter of the telescope command.
set telescope-offset-delimiter-color -- Set color of the telescope command (offset delimiter).
set telescope-offset-separator -- Set offset separator of the telescope command.
set telescope-offset-separator-color -- Set color of the telescope command (offset separator).
set telescope-register-color -- Set color of the telescope command (register).
set telescope-repeating-marker -- Set repeating values marker of the telescope command.
set telescope-repeating-marker-color -- Set color of the telescope command (repeating values marker).
set telescope-skip-repeating-val -- Set whether to skip repeating values of the telescope command.
set telescope-skip-repeating-val-min -- Set minimum amount of repeated values before skipping lines.
set thread-arena -- Set the address pointed by thread_arena.
set trace-buffer-size -- Set requested size of trace buffer.
set trace-commands -- Set tracing of GDB CLI commands.
set trace-notes -- Set notes string to use for current and future trace runs.
set trace-stop-notes -- Set notes string to use for future tstop commands.
set trace-user -- Set the user name to use for current and future trace runs.
set trust-readonly-sections -- Set mode for reading from readonly sections.
set tui -- TUI configuration variables.
set tui active-border-mode -- Set the attribute mode to use for the active TUI window border.
set tui border-kind -- Set the kind of border for TUI windows.
set tui border-mode -- Set the attribute mode to use for the TUI window borders.
set tui compact-source -- Set whether the TUI source window is compact.
set tui mouse-events -- Set whether TUI mode handles mouse clicks.
set tui tab-width -- Set the tab width, in characters, for the TUI.
set unwind-on-signal, 
   set unwindonsignal -- Set unwinding of stack if a signal is received while in a call dummy.
set unwind-on-terminating-exception -- Set unwinding of stack if std::terminate is called while in call dummy.
set unwind-on-timeout -- Set unwinding of stack if a timeout occurs while in a call dummy.
set use-coredump-filter -- Set whether gcore should consider /proc/PID/coredump_filter.
set use-deprecated-index-sections -- Set whether to use deprecated gdb_index sections.
set variable, set var -- Evaluate expression EXP and assign result to variable VAR.
set verbose -- Set verbosity.
set vmmap-prefer-relpaths -- Set show relative paths by default in vmmap.
set watchdog -- Set watchdog timer.
set width -- Set number of characters where GDB should wrap lines of its output.
set write -- Set writing into executable and core files.
undisplay -- Cancel some expressions to be displayed when program stops.
whatis -- Print data type of expression EXP.
with, w -- Temporarily set SETTING to VALUE, run COMMAND, and restore SETTING.
x -- Examine memory: x/FMT ADDRESS.

Command class: files

add-symbol-file -- Load symbols from FILE, assuming FILE has been dynamically loaded.
add-symbol-file-from-memory -- Load the symbols out of memory from a dynamically loaded object file.
cd -- Set working directory to DIR for debugger.
core-file -- Use FILE as core dump for examining memory and registers.
directory -- Add directory DIR to beginning of search path for source files.
edit -- Edit specified file or function.
exec-file -- Use FILE as program for getting contents of pure memory.
file -- Use FILE as program to be debugged.
forward-search, fo -- Search for regular expression (see regex(3)) from last line listed.
generate-core-file, gcore -- Save a core file with the current state of the debugged process.
list, l -- List specified function or line.
load -- Dynamically load FILE into the running program.
nosharedlibrary -- Unload all shared object library symbols.
path -- Add directory DIR(s) to beginning of search path for object files.
pwd -- Print working directory.
remote -- Manipulate files on the remote system.
remote delete -- Delete a remote file.
remote get -- Copy a remote file to the local system.
remote put -- Copy a local file to the remote system.
remove-symbol-file -- Remove a symbol file added via the add-symbol-file command.
reverse-search, rev -- Search backward for regular expression (see regex(3)) from last line listed.
section -- Change the base address of section SECTION of the exec file to ADDR.
sharedlibrary -- Load shared object library symbols for files matching REGEXP.
symbol-file -- Load symbol table from executable file FILE.

Command class: internals

maintenance, mt -- Commands for use by GDB maintainers.
maintenance agent -- Translate an expression into remote agent bytecode for tracing.
maintenance agent-eval -- Translate an expression into remote agent bytecode for evaluation.
maintenance agent-printf -- Translate an expression into remote agent bytecode for evaluation and display the bytecodes.
maintenance btrace -- Branch tracing maintenance commands.
maintenance btrace clear -- Clears the branch tracing data.
maintenance btrace clear-packet-history -- Clears the branch tracing packet history.
maintenance btrace packet-history -- Print the raw branch tracing data.
maintenance check -- Commands for checking internal gdb state.
maintenance check libthread-db -- Run integrity checks on the current inferior's libthread_db.
maintenance check xml-descriptions -- Check equality of GDB target descriptions and XML created descriptions.
maintenance check-psymtabs -- Check consistency of currently expanded psymtabs versus symtabs.
maintenance check-symtabs -- Check consistency of currently expanded symtabs.
maintenance cplus, maintenance cp -- C++ maintenance commands.
maintenance cplus first_component -- Print the first class/namespace component of NAME.
maintenance demangler-warning -- Give GDB a demangler warning.
maintenance deprecate -- Deprecate a command (for testing purposes).
maintenance dump-me -- Get fatal error; make debugger dump its core.
maintenance expand-symtabs -- Expand symbol tables.
maintenance flush -- Maintenance command for flushing GDB internal caches.
maintenance flush dcache -- Force gdb to flush its target memory data cache.
maintenance flush register-cache -- Force gdb to flush its register and frame cache.
maintenance flush source-cache -- Force gdb to flush its source code cache.
maintenance flush symbol-cache -- Flush the symbol cache for each program space.
maintenance ignore-probes -- Ignore probes.
maintenance info, 
   maintenance i -- Commands for showing internal info about the program being debugged.
maintenance info bfds -- List the BFDs that are currently open.
maintenance info breakpoints -- Status of all breakpoints, or breakpoint number NUMBER.
maintenance info btrace -- Info about branch tracing data.
maintenance info frame-unwinders -- List the frame unwinders currently in effect, starting with the highest priority.
maintenance info jit -- Print information about JIT-ed code objects.
maintenance info line-table -- List the contents of all line tables, from all symbol tables.
maintenance info linux-lwps -- List the Linux LWPS.
maintenance info program-spaces -- Info about currently known program spaces.
maintenance info psymtabs -- List the partial symbol tables for all object files.
maintenance info screen -- Show screen characteristics.
maintenance info sections -- List the BFD sections of the exec and core files.
maintenance info selftests -- List the registered selftests.
maintenance info symtabs -- List the full symbol tables for all object files.
maintenance info target-sections -- List GDB's internal section table.
maintenance internal-error -- Give GDB an internal error.
maintenance internal-warning -- Give GDB an internal warning.
maintenance packet -- Send an arbitrary packet to a remote target.
maintenance print -- Maintenance command for printing GDB internal state.
maintenance print architecture -- Print the internal architecture configuration.
maintenance print c-tdesc -- Print the current target description as a C source file.
maintenance print cooked-registers -- Print the internal register configuration including cooked values.
maintenance print core-file-backed-mappings -- Print core file's file-backed mappings.
maintenance print dummy-frames -- Print the contents of the internal dummy-frame stack.
maintenance print frame-id -- Print the current frame-id.
maintenance print msymbols -- Print dump of current minimal symbol definitions.
maintenance print objfiles -- Print dump of current object file definitions.
maintenance print psymbols -- Print dump of current partial symbol definitions.
maintenance print raw-registers -- Print the internal register configuration including raw values.
maintenance print record-instruction -- Print a recorded instruction.
maintenance print reggroups -- Print the internal register group names.
maintenance print register-groups -- Print the internal register configuration including each register's group.
maintenance print registers -- Print the internal register configuration.
maintenance print remote-registers -- Print the internal register configuration including remote register number and g/G packets offset.
maintenance print statistics -- Print statistics about internal gdb state.
maintenance print symbol-cache -- Dump the symbol cache for each program space.
maintenance print symbol-cache-statistics -- Print symbol cache statistics for each program space.
maintenance print symbols -- Print dump of current symbol definitions.
maintenance print target-stack -- Print the name of each layer of the internal target stack.
maintenance print type -- Print a type chain for a given symbol.
maintenance print user-registers -- List the names of the current user registers.
maintenance print xml-tdesc -- Print the current target description as an XML file.
maintenance selftest -- Run gdb's unit tests.
maintenance set -- Set GDB internal variables used by the GDB maintainer.
maintenance set ada -- Set Ada maintenance-related variables.
maintenance set ada ignore-descriptive-types -- Set whether descriptive types generated by GNAT should be ignored.
maintenance set backtrace-on-fatal-signal -- Set whether to produce a backtrace if GDB receives a fatal signal.
maintenance set bfd-sharing -- Set whether gdb will share bfds that appear to be the same file.
maintenance set btrace -- Set branch tracing specific variables.
maintenance set btrace pt -- Set Intel Processor Trace specific variables.
maintenance set btrace pt skip-pad -- Set whether PAD packets should be skipped in the btrace packet history.
maintenance set catch-demangler-crashes -- Set whether to attempt to catch demangler crashes.
maintenance set check-libthread-db -- Set whether to check libthread_db at load time.
maintenance set debuginfod -- Set debuginfod specific variables.
maintenance set debuginfod download-sections -- Set whether debuginfod may download individual ELF/DWARF sections.
maintenance set demangler-warning -- Configure what GDB does when demangler-warning is detected.
maintenance set demangler-warning quit -- Set whether GDB should quit when an demangler-warning is detected.
maintenance set dwarf -- Set DWARF specific variables.
maintenance set dwarf always-disassemble -- Set whether `info address' always disassembles DWARF expressions.
maintenance set dwarf max-cache-age -- Set the upper bound on the age of cached DWARF compilation units.
maintenance set dwarf synchronous -- Set whether DWARF is read synchronously.
maintenance set dwarf unwinders -- Set whether the DWARF stack frame unwinders are used.
maintenance set gnu-source-highlight -- Set gnu-source-highlight specific variables.
maintenance set gnu-source-highlight enabled -- Set whether the GNU Source Highlight library should be used.
maintenance set ignore-prologue-end-flag -- Set if the PROLOGUE-END flag is ignored.
maintenance set internal-error -- Configure what GDB does when internal-error is detected.
maintenance set internal-error backtrace -- Set whether GDB should print a backtrace of GDB when internal-error is detected.
maintenance set internal-error corefile -- Set whether GDB should create a core file of GDB when internal-error is detected.
maintenance set internal-error quit -- Set whether GDB should quit when an internal-error is detected.
maintenance set internal-warning -- Configure what GDB does when internal-warning is detected.
maintenance set internal-warning backtrace -- Set whether GDB should print a backtrace of GDB when internal-warning is detected.
maintenance set internal-warning corefile -- Set whether GDB should create a core file of GDB when internal-warning is detected.
maintenance set internal-warning quit -- Set whether GDB should quit when an internal-warning is detected.
maintenance set libopcodes-styling -- Set libopcodes-styling specific variables.
maintenance set libopcodes-styling enabled -- Set whether the libopcodes styling support should be used.
maintenance set per-command -- Per-command statistics settings.
maintenance set per-command space -- Set whether to display per-command space usage.
maintenance set per-command symtab -- Set whether to display per-command symtab statistics.
maintenance set per-command time -- Set whether to display per-command execution time.
maintenance set profile -- Set internal profiling.
maintenance set selftest -- Self tests-related settings.
maintenance set selftest verbose -- Set whether selftests run in verbose mode.
maintenance set show-debug-regs -- Set whether to show variables that mirror the x86 debug registers.
maintenance set symbol-cache-size -- Set the size of the symbol cache.
maintenance set target-async -- Set whether gdb controls the inferior in asynchronous mode.
maintenance set target-non-stop -- Set whether gdb always controls the inferior in non-stop mode.
maintenance set test-settings -- Set GDB internal variables used for set/show command infrastructure testing.
maintenance set test-settings auto-boolean -- command used for internal testing.
maintenance set test-settings boolean -- command used for internal testing.
maintenance set test-settings enum -- command used for internal testing.
maintenance set test-settings filename -- command used for internal testing.
maintenance set test-settings integer -- command used for internal testing.
maintenance set test-settings optional-filename -- command used for internal testing.
maintenance set test-settings string -- command used for internal testing.
maintenance set test-settings string-noescape -- command used for internal testing.
maintenance set test-settings uinteger -- command used for internal testing.
maintenance set test-settings zinteger -- command used for internal testing.
maintenance set test-settings zuinteger -- command used for internal testing.
maintenance set test-settings zuinteger-unlimited -- command used for internal testing.
maintenance set tui-left-margin-verbose -- Set whether the left margin should use '_' and '0' instead of spaces.
maintenance set tui-resize-message -- Set TUI resize messaging.
maintenance set worker-threads -- Set the number of worker threads GDB can use.
maintenance show -- Show GDB internal variables used by the GDB maintainer.
maintenance show ada -- Show Ada maintenance-related variables.
maintenance show ada ignore-descriptive-types -- Show whether descriptive types generated by GNAT should be ignored.
maintenance show backtrace-on-fatal-signal -- Show whether GDB will produce a backtrace if it receives a fatal signal.
maintenance show bfd-sharing -- Show whether gdb will share bfds that appear to be the same file.
maintenance show btrace -- Show branch tracing specific variables.
maintenance show btrace pt -- Show Intel Processor Trace specific variables.
maintenance show btrace pt skip-pad -- Show whether PAD packets should be skipped in the btrace packet history.
maintenance show catch-demangler-crashes -- Show whether to attempt to catch demangler crashes.
maintenance show check-libthread-db -- Show whether to check libthread_db at load time.
maintenance show debuginfod -- Show debuginfod specific variables.
maintenance show debuginfod download-sections -- Show whether debuginfod may download individual ELF/DWARF sections.
maintenance show demangler-warning -- Show what GDB does when demangler-warning is detected.
maintenance show demangler-warning quit -- Show whether GDB will quit when an demangler-warning is detected.
maintenance show dwarf -- Show DWARF specific variables.
maintenance show dwarf always-disassemble -- Show whether `info address' always disassembles DWARF expressions.
maintenance show dwarf max-cache-age -- Show the upper bound on the age of cached DWARF compilation units.
maintenance show dwarf synchronous -- Show whether DWARF is read synchronously.
maintenance show dwarf unwinders -- Show whether the DWARF stack frame unwinders are used.
maintenance show gnu-source-highlight -- Show gnu-source-highlight specific variables.
maintenance show gnu-source-highlight enabled -- Show whether the GNU Source Highlight library is being used.
maintenance show ignore-prologue-end-flag -- Show if the PROLOGUE-END flag is ignored.
maintenance show internal-error -- Show what GDB does when internal-error is detected.
maintenance show internal-error backtrace -- Show whether GDB will print a backtrace of GDB when internal-error is detected.
maintenance show internal-error corefile -- Show whether GDB will create a core file of GDB when internal-error is detected.
maintenance show internal-error quit -- Show whether GDB will quit when an internal-error is detected.
maintenance show internal-warning -- Show what GDB does when internal-warning is detected.
maintenance show internal-warning backtrace -- Show whether GDB will print a backtrace of GDB when internal-warning is detected.
maintenance show internal-warning corefile -- Show whether GDB will create a core file of GDB when internal-warning is detected.
maintenance show internal-warning quit -- Show whether GDB will quit when an internal-warning is detected.
maintenance show libopcodes-styling -- Show libopcodes-styling specific variables.
maintenance show libopcodes-styling enabled -- Show whether the libopcodes styling support should be used.
maintenance show per-command -- Show per-command statistics settings.
maintenance show per-command space -- Show whether to display per-command space usage.
maintenance show per-command symtab -- Show whether to display per-command symtab statistics.
maintenance show per-command time -- Show whether to display per-command execution time.
maintenance show profile -- Show internal profiling.
maintenance show selftest -- Self tests-related settings.
maintenance show selftest verbose -- Show whether selftests run in verbose mode.
maintenance show show-debug-regs -- Show whether to show variables that mirror the x86 debug registers.
maintenance show symbol-cache-size -- Show the size of the symbol cache.
maintenance show target-async -- Show whether gdb controls the inferior in asynchronous mode.
maintenance show target-non-stop -- Show whether gdb always controls the inferior in non-stop mode.
maintenance show test-options-completion-result -- Show maintenance test-options completion result.
maintenance show test-settings -- Show GDB internal variables used for set/show command infrastructure testing.
maintenance show test-settings auto-boolean -- command used for internal testing.
maintenance show test-settings boolean -- command used for internal testing.
maintenance show test-settings enum -- command used for internal testing.
maintenance show test-settings filename -- command used for internal testing.
maintenance show test-settings integer -- command used for internal testing.
maintenance show test-settings optional-filename -- command used for internal testing.
maintenance show test-settings string -- command used for internal testing.
maintenance show test-settings string-noescape -- command used for internal testing.
maintenance show test-settings uinteger -- command used for internal testing.
maintenance show test-settings zinteger -- command used for internal testing.
maintenance show test-settings zuinteger -- command used for internal testing.
maintenance show test-settings zuinteger-unlimited -- command used for internal testing.
maintenance show tui-left-margin-verbose -- Show whether the left margin should use '_' and '0' instead of spaces.
maintenance show tui-resize-message -- Show TUI resize messaging.
maintenance show worker-threads -- Show the number of worker threads GDB can use.
maintenance space -- Set the display of space usage.
maintenance test-options -- Generic command for testing the options infrastructure.
maintenance test-options require-delimiter -- Command used for testing options processing.
maintenance test-options unknown-is-error -- Command used for testing options processing.
maintenance test-options unknown-is-operand -- Command used for testing options processing.
maintenance time -- Set the display of time usage.
maintenance translate-address -- Translate a section name and address to a symbol.
maintenance undeprecate -- Undeprecate a command (for testing purposes).
maintenance wait-for-index-cache -- Wait until all pending writes to the index cache have completed.
maintenance with -- Like "with", but works with "maintenance set" variables.

Command class: obscure

checkpoint -- Fork a duplicate process (experimental).
compare-sections -- Compare section data on target to the exec file.
compile, expression -- Command to compile source code and inject it into the inferior.
compile code -- Compile, inject, and execute code.
compile file -- Evaluate a file containing source code.
compile print -- Evaluate EXPR by using the compiler and print result.
complete -- List the completions for the rest of the line as a command.
guile, gu -- Evaluate a Guile expression.
guile-repl, gr -- Start a Guile interactive prompt.
monitor -- Send a command to the remote monitor (remote targets only).
python, py -- Evaluate a Python command.
python-interactive, pi -- Start an interactive Python prompt.
record, rec -- Start recording.
record btrace, record b -- Start branch trace recording.
record btrace bts, record bts -- Start branch trace recording in Branch Trace Store (BTS) format.
record btrace pt, record pt -- Start branch trace recording in Intel Processor Trace format.
record delete, record del, 
   record d -- Delete the rest of execution log and start recording it anew.
record full -- Start full execution recording.
record full restore -- Restore the execution log from a file.
record function-call-history -- Prints the execution history at function granularity.
record goto -- Restore the program to its state at instruction number N.
record goto begin, record goto start -- Go to the beginning of the execution log.
record goto end -- Go to the end of the execution log.
record instruction-history -- Print disassembled instructions stored in the execution log.
record save -- Save the execution log to a file.
record stop, record s -- Stop the record/replay target.
restart -- Restore program context from a checkpoint.
stop -- There is no `stop' command, but you can set a hook on `stop'.

Command class: running

advance -- Continue the program up to the given location (same form as args for break command).
attach -- Attach to a process or file outside of GDB.
continue, fg, c -- Continue program being debugged, after signal or breakpoint.
detach -- Detach a process or file previously attached.
detach checkpoint -- Detach from a checkpoint (experimental).
detach inferiors -- Detach from inferior ID (or list of IDS).
disconnect -- Disconnect from a target.
finish, fin -- Execute until selected stack frame returns.
handle -- Specify how to handle signals.
inferior -- Use this command to switch between inferiors.
interrupt -- Interrupt the execution of the debugged program.
jump -- Continue program being debugged at specified line or address.
kill -- Kill execution of program being debugged.
kill inferiors -- Kill inferior ID (or list of IDs).
next, n -- Step program, proceeding through subroutine calls.
nexti, ni -- Step one instruction, but proceed through subroutine calls.
queue-signal -- Queue a signal to be delivered to the current thread when it is resumed.
reverse-continue, rc -- Continue program being debugged but run it in reverse.
reverse-finish -- Execute backward until just before selected stack frame is called.
reverse-next, rn -- Step program backward, proceeding through subroutine calls.
reverse-nexti, rni -- Step backward one instruction, but proceed through called subroutines.
reverse-step, rs -- Step program backward until it reaches the beginning of another source line.
reverse-stepi, rsi -- Step backward exactly one instruction.
run, r -- Start debugged program.
signal -- Continue program with the specified signal.
starti -- Start the debugged program stopping at the first instruction.
step, s -- Step program until it reaches a different source line.
stepi, si -- Step one instruction exactly.
taas -- Apply a command to all threads (ignoring errors and empty output).
target -- Connect to a target machine or process.
target core -- Use a core file as a target.
target ctf -- (Use a CTF directory as a target.
target exec -- Use an executable file as a target.
target extended-remote -- Use a remote computer via a serial line, using a gdb-specific protocol.
target native -- Native process (started by the "run" command).
target record-btrace -- Collect control-flow trace and provide the execution history.
target record-core -- Log program while executing and replay execution from log.
target record-full -- Log program while executing and replay execution from log.
target remote -- Use a remote computer via a serial line, using a gdb-specific protocol.
target tfile -- Use a trace file as a target.
task -- Use this command to switch between Ada tasks.
task apply -- Apply a command to a list of tasks.
task apply all -- Apply a command to all tasks in the current inferior.
tfaas -- Apply a command to all frames of all threads (ignoring errors and empty output).
thread, t -- Use this command to switch between threads.
thread apply -- Apply a command to a list of threads.
thread apply all -- Apply a command to all threads.
thread find -- Find threads that match a regular expression.
thread name -- Set the current thread's name.
until -- Execute until past the current line or past a LOCATION.

Command class: status

info, inf, i -- Generic command for showing things about the program being debugged.
info address -- Describe where symbol SYM is stored.
info all-registers -- List of all registers and their contents, for selected stack frame.
info args -- All argument variables of current stack frame or those matching REGEXPs.
info auto-load -- Print current status of auto-loaded files.
info auto-load gdb-scripts -- Print the list of automatically loaded sequences of commands.
info auto-load libthread-db -- Print the list of loaded inferior specific libthread_db.
info auto-load local-gdbinit -- Print whether current directory .gdbinit file has been loaded.
info auto-load python-scripts -- Print the list of automatically loaded Python scripts.
info auxv -- Display the inferior's auxiliary vector.
info bookmarks -- Status of user-settable bookmarks.
info breakpoints, 
   info b -- Status of specified breakpoints (all user-settable breakpoints if no argument).
info checkpoints -- IDs of currently known checkpoints.
info classes -- All Objective-C classes, or those matching REGEXP.
info common -- Print out the values contained in a Fortran COMMON block.
info connections -- Target connections in use.
info copying -- Conditions for redistributing copies of GDB.
info dcache -- Print information on the dcache performance.
info display -- Expressions to display when program stops, with code numbers.
info exceptions -- List all Ada exception names.
info extensions -- All filename extensions associated with a source language.
info files -- Names of targets and files being debugged.
info float -- Print the status of the floating point unit.
info frame, info f -- All about the selected stack frame.
info frame address -- Print information about a stack frame selected by stack address.
info frame function -- Print information about a stack frame selected by function name.
info frame level -- Print information about a stack frame selected by level.
info frame view -- Print information about a stack frame outside the current backtrace.
info frame-filter -- List all registered Python frame-filters.
info functions -- All function names or those matching REGEXPs.
info guile, info gu -- Prefix command for Guile info displays.
info inferiors -- Print a list of inferiors being managed.
info line -- Core addresses of the code for a source line.
info locals -- All local variables of current stack frame or those matching REGEXPs.
info macro -- Show the definition of MACRO, and it's source location.
info macros -- Show the definitions of all macros at LINESPEC, or the current source location.
info main -- Get main symbol to identify entry point into program.
info mem -- Memory region attributes.
info missing-debug-handlers -- GDB command to list missing debug handlers.
info module -- Print information about modules.
info module functions -- Display functions arranged by modules.
info module variables -- Display variables arranged by modules.
info modules -- All module names, or those matching REGEXP.
info os -- Show OS data ARG.
info pretty-printer -- GDB command to list all registered pretty-printers.
info probes -- Show available static probes.
info probes all -- Show information about all type of probes.
info probes dtrace -- Show information about DTrace static probes.
info probes stap -- Show information about SystemTap static probes.
info proc -- Show additional information about a process.
info proc all -- List all available info about the specified process.
info proc cmdline -- List command line arguments of the specified process.
info proc cwd -- List current working directory of the specified process.
info proc exe -- List absolute filename for executable of the specified process.
info proc files -- List files opened by the specified process.
info proc mappings -- List memory regions mapped by the specified process.
info proc stat -- List process info from /proc/PID/stat.
info proc status -- List process info from /proc/PID/status.
info program -- Execution status of the program.
info record, info rec -- Info record options.
info registers, info r -- List of integer registers and their contents, for selected stack frame.
info scope -- List the variables local to a scope.
info selectors -- All Objective-C selectors, or those matching REGEXP.
info sharedlibrary, info dll -- Status of loaded shared object libraries.
info signals, info handle -- What debugger does when program gets various signals.
info skip -- Display the status of skips.
info source -- Information about the current source file.
info sources -- All source files in the program or those matching REGEXP.
info stack, info s -- Backtrace of the stack, or innermost COUNT frames.
info static-tracepoint-markers -- List target static tracepoints markers.
info symbol -- Describe what symbol is at location ADDR.
info target -- Names of targets and files being debugged.
info tasks -- Provide information about all known Ada tasks.
info terminal -- Print inferior's saved terminal status.
info threads -- Display currently known threads.
info tracepoints, info tp -- Status of specified tracepoints (all tracepoints if no argument).
info tvariables -- Status of trace state variables and their values.
info type-printers -- GDB command to list all registered type-printers.
info types -- All type names, or those matching REGEXP.
info unwinder -- GDB command to list unwinders.
info variables -- All global and static variable names or those matching REGEXPs.
info vector -- Print the status of the vector unit.
info vtbl -- Show the virtual function table for a C++ object.
info warranty -- Various kinds of warranty you do not have.
info watchpoints -- Status of specified watchpoints (all watchpoints if no argument).
info win -- List of all displayed windows.
info xmethod -- GDB command to list registered xmethod matchers.
macro -- Prefix for commands dealing with C preprocessor macros.
macro define -- Define a new C/C++ preprocessor macro.
macro expand, macro exp -- Fully expand any C/C++ preprocessor macro invocations in EXPRESSION.
macro expand-once, 
   macro exp1 -- Expand C/C++ preprocessor macro invocations appearing directly in EXPRESSION.
macro list -- List all the macros defined using the `macro define' command.
macro undef -- Remove the definition of the C/C++ preprocessor macro with the given name.
show, info set -- Generic command for showing things about the debugger.
show ada -- Generic command for showing Ada-specific settings.
show ada print-signatures -- Show whether the output of formal and return types for functions in the overloads selection menu is activated.
show ada source-charset -- Show the Ada source character set.
show ada trust-PAD-over-XVS -- Show whether an optimization trusting PAD types over XVS types is activated.
show agent -- Show debugger's willingness to use agent as a helper.
show ai-anthropic-api-key -- Show Anthropic API key.
show ai-history-size -- Show maximum number of questions and answers to keep in the prompt.
show ai-max-tokens -- Show the maximum number of tokens to return in the response.
show ai-model -- Show the name of the large language model to query.
show ai-ollama-endpoint -- Show Ollama API endpoint.
show ai-openai-api-key -- Show OpenAI API key.
show ai-show-usage -- Show whether to show how many tokens are used with each OpenAI API call.
show ai-stack-depth -- Show rows of stack context to include in the prompt for the ai command.
show ai-temperature -- Show the temperature specification for the LLM query.
show always-read-ctf -- Show whether CTF is always read.
show annotate -- Show annotation_level.
show architecture -- Show architecture of target.
show args -- Show argument list to give program being debugged when it is started.
show attachp-resolution-method -- Show how to determine the process to attach when multiple candidates exists.
show auto-connect-native-target -- Show whether GDB may automatically connect to the native target.
show auto-explore-auxv -- Show stack exploration for AUXV information; it may be really slow.
show auto-explore-pages -- Show whether to try to infer page permissions when memory maps are missing.
show auto-explore-stack -- Show stack exploration; it may be really slow.
show auto-load -- Show auto-loading specific settings.
show auto-load gdb-scripts -- Show whether auto-loading of canned sequences of commands scripts is enabled.
show auto-load libthread-db -- Show whether auto-loading inferior specific libthread_db is enabled.
show auto-load local-gdbinit -- Show whether auto-loading .gdbinit script in current directory is enabled.
show auto-load python-scripts -- Show the debugger's behaviour regarding auto-loaded Python scripts.
show auto-load safe-path -- Show the list of files and directories that are safe for auto-loading.
show auto-load scripts-directory -- Show the list of directories from which to load auto-loaded scripts.
show auto-save-search -- Show automatically pass --save to "search" command.
show auto-solib-add -- Show autoloading of shared library symbols.
show backtrace -- Show backtrace specific variables.
show backtrace limit -- Show the upper bound on the number of backtrace levels.
show backtrace past-entry -- Show whether backtraces should continue past the entry point of a program.
show backtrace past-main -- Show whether backtraces should continue past "main".
show backtrace-address-color -- Show color for backtrace (address).
show backtrace-frame-label -- Show frame number label for backtrace.
show backtrace-frame-label-color -- Show color for backtrace (frame label).
show backtrace-prefix -- Show prefix for current backtrace label.
show backtrace-prefix-color -- Show color for prefix of current backtrace label.
show backtrace-symbol-color -- Show color for backtrace (symbol).
show banner-color -- Show color for banner line.
show banner-separator -- Show repeated banner separator character.
show banner-title-color -- Show color for banner title.
show banner-title-position -- Show banner title position.
show banner-title-surrounding-left -- Show banner title surrounding char (left side).
show banner-title-surrounding-right -- Show banner title surrounding char (right side).
show basenames-may-differ -- Show whether a source file may have multiple base names.
show bn-autosync -- Show whether to automatically run bn-sync every step.
show bn-decomp-style -- Show decompilation highlight theme for Binary Ninja.
show bn-il-level -- Show the IL level to use when displaying Binary Ninja decompilation.
show bn-rpc-host -- Show Binary Ninja XML-RPC server host.
show bn-rpc-port -- Show Binary Ninja XML-RPC server port.
show bn-timeout -- Show time to wait for Binary Ninja XML-RPC, in seconds.
show breakpoint -- Breakpoint specific settings.
show breakpoint always-inserted -- Show mode for inserting breakpoints.
show breakpoint auto-hw -- Show automatic usage of hardware breakpoints.
show breakpoint condition-evaluation -- Show mode of breakpoint condition evaluation.
show breakpoint pending -- Show debugger's behavior regarding pending breakpoints.
show can-use-hw-watchpoints -- Show debugger's willingness to use watchpoint hardware.
show case-sensitive -- Show case sensitivity in name search (on/off/auto).
show chain-arrow-color -- Show color of chain formatting (arrow).
show chain-arrow-left -- Show left arrow of chain formatting.
show chain-arrow-right -- Show right arrow of chain formatting.
show chain-contiguous-marker -- Show contiguous marker of chain formatting.
show chain-contiguous-marker-color -- Show color of chain formatting (contiguous marker).
show charset -- Show the host and target character sets.
show check, show ch, show c -- Show the status of the type/range checker.
show check range -- Show range checking (on/warn/off/auto).
show check type -- Show strict type checking.
show circular-trace-buffer -- Show target's use of circular trace buffer.
show code-cache -- Show cache use for code segment access.
show code-prefix -- Show prefix marker for 'context code' command.
show code-prefix-color -- Show color for 'context code' command (prefix marker).
show coerce-float-to-double -- Show coercion of floats to doubles when calling functions.
show commands -- Show the history of commands you typed.
show comment-color -- Show color for comment.
show compile-args -- Show compile command GCC command-line arguments.
show compile-gcc -- Show compile command GCC driver filename.
show complaints -- Show max number of complaints about incorrect symbols.
show configuration -- Show how GDB was configured at build time.
show confirm -- Show whether to confirm potentially dangerous operations.
show context-backtrace-lines -- Show number of lines to print in the backtrace context.
show context-clear-screen -- Show whether to clear the screen before printing the context.
show context-code-lines -- Show number of source code lines to print by the context command.
show context-code-tabstop -- Show number of spaces that a <tab> in the source code counts for.
show context-disasm-lines -- Show number of additional lines to print in the disasm context.
show context-flag-bracket-color -- Show color for flags register (bracket).
show context-flag-changed-color -- Show color for flags register (flag changed).
show context-flag-set-color -- Show color for flags register (flag set).
show context-flag-unset-color -- Show color for flags register (flag unset).
show context-flag-value-color -- Show color for flags register (register value).
show context-ghidra -- Show when to try to decompile the current function with ghidra.
show context-history-size -- Show number of context history entries to store.
show context-integration-decompile -- Show whether context should fall back to decompilation with no source code.
show context-max-threads -- Show maximum number of threads displayed by the context command.
show context-output -- Show where Pwndbg should output ("stdout" or file/tty).
show context-register-changed-color -- Show color for registers label (change marker).
show context-register-changed-marker -- Show change marker for registers label.
show context-register-color -- Show color for registers label.
show context-reserve-lines -- Show when to reserve lines after the prompt to reduce context shake.
show context-sections -- Show which context sections are displayed (controls order).
show context-stack-lines -- Show number of lines to print in the stack context.
show convenience, show conv -- Debugger convenience ("$foo") variables and functions.
show copying -- Conditions for redistributing copies of GDB.
show cp-abi -- Show the ABI used for inspecting C++ objects.
show cwd -- Show the current working directory that is used when the inferior is started.
show cymbol-editor -- Show path to the editor for editing custom structures.
show data-directory -- Show GDB's data directory.
show dcache -- Show dcache settings.
show dcache line-size -- Show dcache line size.
show dcache size -- Show number of dcache lines.
show debug -- Generic command for showing gdb debugging flags.
show debug arch -- Show architecture debugging.
show debug auto-load -- Show auto-load verifications debugging.
show debug bfd-cache -- Show bfd cache debugging.
show debug breakpoint -- Show breakpoint location debugging.
show debug check-physname -- Show cross-checking of "physname" code against demangler.
show debug coff-pe-read -- Show coff PE read debugging.
show debug compile -- Show compile command debugging.
show debug compile-cplus-scopes -- Show debugging of C++ compile scopes.
show debug compile-cplus-types -- Show debugging of C++ compile type conversion.
show debug displaced -- Show displaced stepping debugging.
show debug dwarf-die -- Show debugging of the DWARF DIE reader.
show debug dwarf-line -- Show debugging of the dwarf line reader.
show debug dwarf-read -- Show debugging of the DWARF reader.
show debug entry-values -- Show entry values and tail call frames debugging.
show debug event-loop -- Show event-loop debugging.
show debug expression -- Show expression debugging.
show debug fortran-array-slicing -- Show debugging of Fortran array slicing.
show debug frame -- Show frame debugging.
show debug index-cache -- Show display of index-cache debug messages.
show debug infcall -- Show inferior call debugging.
show debug infrun -- Show inferior debugging.
show debug jit -- Show JIT debugging.
show debug libthread-db -- Show libthread-db debugging.
show debug linux-namespaces -- Show debugging of GNU/Linux namespaces module.
show debug linux-nat -- 	Show debugging of GNU/Linux native target.
show debug notification -- Show debugging of async remote notification.
show debug observer -- Show observer debugging.
show debug overload -- Show debugging of C++ overloading.
show debug parser -- Show parser debugging.
show debug py-breakpoint -- Show Python breakpoint debugging.
show debug py-micmd -- Show Python micmd debugging.
show debug py-unwind -- Show Python unwinder debugging.
show debug record -- Show debugging of record/replay feature.
show debug remote -- Show debugging of remote protocol.
show debug remote-packet-max-chars -- Show the maximum number of characters to display for each remote packet.
show debug separate-debug-file -- Show printing of separate debug info file search debug.
show debug serial -- Show serial debugging.
show debug skip -- Show whether the debug output about skipping files and functions is printed.
show debug solib -- Show solib debugging.
show debug stap-expression -- Show SystemTap expression debugging.
show debug symbol-lookup -- Show debugging of symbol lookup.
show debug symfile -- Show debugging of the symfile functions.
show debug symtab-create -- Show debugging of symbol table creation.
show debug target -- Show target debugging.
show debug threads -- Show thread debugging.
show debug timestamp -- Show timestamping of debugging messages.
show debug tui -- Show tui debugging.
show debug varobj -- Show varobj debugging.
show debug xml -- Show XML parser debugging.
show debug-events -- Show display internal event debugging info.
show debug-file-directory -- Show the directories where separate debug symbols are searched for.
show debuginfod -- Show debuginfod options.
show debuginfod enabled -- Show whether to use debuginfod.
show debuginfod urls -- Show the list of debuginfod server URLs.
show debuginfod verbose -- Show debuginfod debugging.
show decompiler -- Show framework that your ghidra plugin installed.
show default-collect -- Show the list of expressions to collect by default.
show default-visualize-chunk-number -- Show default number of chunks to visualize.
show demangle-style -- Show the current C++ demangling style.
show dereference-limit -- Show max number of pointers to dereference in a chain.
show detach-on-fork -- Show whether gdb will detach the child of a fork.
show direct-call-timeout -- Show the timeout, for direct calls to inferior function calls.
show directories -- Show the search path for finding source files.
show disable-colors -- Show whether to color the output or not.
show disable-randomization -- Show disabling of debuggee's virtual address space randomization.
show disasm-annotations -- Show display annotations for instructions.
show disasm-branch-color -- Show color for disasm (branch/call instruction).
show disasm-branch-off -- Show marker for branches that will NOT be taken.
show disasm-branch-on -- Show marker for branches that WILL be taken.
show disasm-inline-symbols -- Show replacing constant operands with their symbol in the disassembly.
show disasm-reg-alias -- Show force the disassembly to use register aliases (e.g. aarch64 x29 -> fp).
show disasm-telescope-depth -- Show depth of telescope for disasm annotations.
show disasm-telescope-string-length -- Show the number of characters in strings to display in disasm annotations.
show disassemble-next-line -- Show whether to disassemble next source line or insn when execution stops.
show disassembler-options -- Show the disassembler options.
show disassembly-flavor -- Show the disassembly flavor.
show disconnected-dprintf -- Show whether dprintf continues after GDB disconnects.
show disconnected-tracing -- Show whether tracing continues after GDB disconnects.
show displaced-stepping -- Show debugger's willingness to use displaced stepping.
show dprintf-channel -- Show the channel to use for dynamic printf.
show dprintf-function -- Show the function to use for dynamic printf.
show dprintf-style -- Show the style of usage for dynamic printf.
show dump-excluded-mappings -- Show whether gcore should dump mappings marked with the VM_DONTDUMP flag.
show editing -- Show editing of command lines as they are typed.
show emulate -- Show unicorn emulation of code from the current PC register.
show emulate-annotations -- Show unicorn emulation for instruction annotations.
show emulate-future-annotations -- Show unicorn emulation for future instruction's annotations.
show endian -- Show endianness of target.
show enhance-comment-color -- Show color of value enhance (comment).
show enhance-integer-value-color -- Show color of value enhance (integer).
show enhance-string-value-color -- Show color of value enhance (string).
show enhance-unknown-color -- Show color of value enhance (unknown value).
show environment -- The environment to give the program, or one variable's value.
show exception-debugger -- Show whether to debug exceptions raised in Pwndbg commands.
show exception-verbose -- Show print a full stacktrace for exceptions raised in Pwndbg commands.
show exec-direction -- Show direction of execution (forward/reverse).
show exec-done-display -- Show notification of completion for asynchronous execution commands.
show exec-file-mismatch -- Show exec-file-mismatch handling (ask|warn|off).
show exec-wrapper -- Show the wrapper for running programs.
show extended-prompt -- Show the extended prompt.
show extension-language -- Show mapping between filename extension and source language.
show filename-display -- Show how to display filenames.
show follow-exec-mode -- Show debugger response to a program call of exec.
show follow-fork-mode -- Show debugger response to a program call of fork or vfork.
show fortran -- Generic command for showing Fortran-specific settings.
show fortran repack-array-slices -- Show whether non-contiguous array slices are repacked.
show frame-filter -- Prefix command for 'show' frame-filter related operations.
show frame-filter priority -- GDB command to show the priority of the specified frame-filter.
show gcc-compiler-path -- Show path to the gcc/g++ toolchain for generating imported symbols.
show gdb-workaround-stop-event -- Show asynchronous stop events to improve 'commands' functionality.
show glibc -- Show glibc version for heap heuristics resolution (e.g. 2.31).
show global-max-fast -- Show the address of global_max_fast.
show gnutarget -- Show the current BFD target.
show go-dump-debug -- Show color for 'go-dump' command's debug info when --debug is specified.
show go-dump-indent-amount -- Show the indent amount for go-dump pretty printing.
show go-dump-line-width -- Show the soft line width for go-dump pretty printing.
show guile, show gu -- Prefix command for Guile preference settings.
show guile print-stack -- Show the mode of Guile exception printing on error.
show heap-corruption-check-limit -- Show amount of chunks to traverse for the bin corruption check.
show heap-dereference-limit -- Show number of chunks to dereference in each bin.
show height -- Show number of lines in a page for GDB output pagination.
show hexdump-address-color -- Show color for hexdump command (address label).
show hexdump-ascii-block-separator -- Show block separator char of the hexdump command.
show hexdump-byte-separator -- Show separator of single bytes in hexdump (does NOT affect group separator).
show hexdump-bytes -- Show number of bytes printed by hexdump command.
show hexdump-colorize-ascii -- Show whether to colorize the hexdump command ascii section.
show hexdump-group-use-big-endian -- Show use big-endian within each group of bytes in hexdump command.
show hexdump-group-width -- Show number of bytes grouped in hexdump command.
show hexdump-highlight-group-lsb -- Show highlight LSB of each group.
show hexdump-limit-mb -- Show the maximum size in megabytes (MB) `hexdump` will read.
show hexdump-normal-color -- Show color for hexdump command (normal bytes).
show hexdump-offset-color -- Show color for hexdump command (offset label).
show hexdump-printable-color -- Show color for hexdump command (printable characters).
show hexdump-separator-color -- Show color for hexdump command (group separator).
show hexdump-special-color -- Show color for hexdump command (special bytes).
show hexdump-width -- Show line width of hexdump command.
show hexdump-zero-color -- Show color for hexdump command (zero bytes).
show highlight-breakpoints -- Show whether to highlight breakpoints.
show highlight-color -- Show color added to highlights like source/pc.
show highlight-pc -- Show whether to highlight the current instruction.
show highlight-source -- Show whether to highlight the closest source line.
show history -- Generic command for showing command history parameters.
show history expansion -- Show history expansion on command input.
show history filename -- Show the filename in which to record the command history.
show history remove-duplicates -- Show how far back in history to look for and remove duplicate entries.
show history save -- Show saving of the history record on exit.
show history size -- Show the size of the command history.
show host-charset -- Show the host character set.
show ida-rpc-host -- Show ida xmlrpc server address.
show ida-rpc-port -- Show ida xmlrpc server port.
show ida-timeout -- Show time to wait for ida xmlrpc in seconds.
show index-cache -- Show index-cache options.
show index-cache directory -- Show the directory of the index cache.
show index-cache enabled -- Show whether the index cache is enabled.
show index-cache stats -- Show some stats about the index cache.
show indirect-call-timeout -- Show the timeout, for indirect calls to inferior function calls.
show inferior-tty -- 		Show terminal for future runs of program being debugged.
show input-radix -- Show default input radix for entering numbers.
show integration-function-lookup -- Show use integration to look up function type signatures.
show integration-provider -- Show which provider to use for integration features.
show integration-smart-enhance -- Show use integration to determine when to disassemble during enhancing.
show integration-symbol-lookup -- Show whether to use integration to look up unknown symbols.
show interactive-mode -- Show whether GDB's standard input is a terminal.
show kernel-vmmap -- Show the method to get vmmap information when debugging via QEMU kernel.
show language -- Show the current source language.
show left-pad-disasm -- Show whether to left-pad disassembly.
show libthread-db-search-path -- Show the current search path or libthread_db.
show listsize -- Show number of source lines gdb will list by default.
show logging -- Show logging options.
show logging debugredirect -- Show the logging debug output mode.
show logging enabled -- Show whether logging is enabled.
show logging file -- Show the current logfile.
show logging overwrite -- Show whether logging overwrites or appends to the log file.
show logging redirect -- Show the logging output mode.
show main-arena -- Show the address of main_arena.
show max-completions -- Show maximum number of completion candidates.
show max-decimal-number -- Show show all numbers greater than this in hex.
show max-user-call-depth -- Show the max call depth for non-python/scheme user-defined commands.
show max-value-size -- Show maximum sized value gdb will load from the inferior.
show max-visualize-chunk-size -- Show max display size for heap chunks visualization (0 for display all).
show may-call-functions -- Show permission to call functions in the program.
show may-insert-breakpoints -- Show permission to insert breakpoints in the target.
show may-insert-fast-tracepoints -- Show permission to insert fast tracepoints in the target.
show may-insert-tracepoints -- Show permission to insert tracepoints in the target.
show may-interrupt -- Show permission to interrupt or signal the target.
show may-write-memory -- Show permission to write into target memory.
show may-write-registers -- Show permission to write into registers.
show mem -- Memory regions settings.
show mem inaccessible-by-default -- Show handling of unknown memory regions.
show memory-code-color -- Show color for executable memory.
show memory-data-color -- Show color for all other writable memory.
show memory-guard-color -- Show color added to all guard pages (no perms).
show memory-heap-color -- Show color for heap memory.
show memory-rodata-color -- Show color for all read only memory.
show memory-stack-color -- Show color for stack memory.
show memory-wx-color -- Show color added to all WX memory.
show message-breakpoint-color -- Show color of breakpoint messages.
show message-debug-color -- Show color of debug messages.
show message-error-color -- Show color of error messages.
show message-exit-color -- Show color of exit messages.
show message-hint-color -- Show color of hint and marker messages.
show message-info-color -- Show color of info messages.
show message-notice-color -- Show color of notice messages.
show message-signal-color -- Show color of signal messages.
show message-status-off-color -- Show color of off status messages.
show message-status-on-color -- Show color of on status messages.
show message-success-color -- Show color of success messages.
show message-system-color -- Show color of system messages.
show message-warning-color -- Show color of warning messages.
show mi-async -- Show whether MI asynchronous mode is enabled.
show mp -- Show the address of mp_.
show mpx -- Show Intel Memory Protection Extensions specific variables.
show multiple-symbols -- Show how the debugger handles ambiguities in expressions.
show nearpc-address-color -- Show color for nearpc command (address).
show nearpc-argument-color -- Show color for nearpc command (target argument).
show nearpc-backwards-lines -- Show number of lines before the pc to print for the nearpc command.
show nearpc-branch-marker -- Show branch marker line for nearpc command.
show nearpc-branch-marker-color -- Show color for nearpc command (branch marker line).
show nearpc-branch-marker-contiguous -- Show contiguous branch marker line for nearpc command.
show nearpc-breakpoint-color -- Show color for nearpc command (breakpoint marker).
show nearpc-breakpoint-prefix -- Show breakpoint marker for nearpc command.
show nearpc-integration-comments -- Show whether to show comments from integration provider.
show nearpc-integration-comments-color -- Show color for nearpc command (integration comments).
show nearpc-lines -- Show number of lines to print for the nearpc command.
show nearpc-num-opcode-bytes -- Show number of opcode bytes to print for each instruction.
show nearpc-opcode-separator-bytes -- Show number of spaces between opcode bytes.
show nearpc-prefix -- Show prefix marker for nearpc command.
show nearpc-prefix-color -- Show color for nearpc command (prefix marker).
show nearpc-show-args -- Show whether to show call arguments below instruction.
show nearpc-symbol-color -- Show color for nearpc command (symbol).
show nearpc-syscall-name-color -- Show color for nearpc command (resolved syscall name).
show ng-search-on-fail -- Show let the ng-slot* commands search the heap if necessary.
show ng-vis-count -- Show default count for ng-vis.
show non-stop -- Show whether gdb controls the inferior in non-stop mode.
show objc-max-function-arguments -- Show maximum number of arguments to resolve for an Objective-C method call.
show objc-max-function-types-depth -- Show maximum allowed depth for a type in an Objective-C method call.
show observer -- Show whether gdb controls the inferior in observer mode.
show opaque-type-resolution -- Show resolution of opaque struct/class/union types (if set before loading symbols).
show osabi -- Show OS ABI of target.
show output-radix -- Show default output radix for printing of values.
show overload-resolution -- Show overload resolution in evaluating C++ functions.
show pagination -- Show state of GDB output pagination.
show paths -- Current search path for finding object files.
show print, show pr, show p -- Generic command for showing print settings.
show print address -- Show printing of addresses.
show print array -- Show pretty formatting of arrays.
show print array-indexes -- Show printing of array indexes.
show print asm-demangle -- Show demangling of C++/ObjC names in disassembly listings.
show print characters -- Show limit on string chars to print.
show print demangle -- Show demangling of encoded C++/ObjC names when displaying symbols.
show print elements -- Show limit on array elements to print.
show print entry-values -- Show printing of function arguments at function entry.
show print finish -- Show whether `finish' prints the return value.
show print frame-arguments -- Show printing of non-scalar frame arguments.
show print frame-info -- Show printing of frame information.
show print inferior-events -- Show printing of inferior events (such as inferior start and exit).
show print max-depth -- Show maximum print depth for nested structures, unions, and arrays.
show print max-symbolic-offset -- Show the largest offset that will be printed in <SYMBOL+1234> form.
show print memory-tag-violations -- Show printing of memory tag violations for pointers.
show print nibbles -- Show whether to print binary values in groups of four bits.
show print null-stop -- Show printing of char arrays to stop at first null char.
show print object -- Show printing of C++ virtual function tables.
show print pascal_static-members -- Show printing of pascal static members.
show print pretty -- Show pretty formatting of structures.
show print raw-frame-arguments -- Show whether to print frame arguments in raw form.
show print raw-values -- Show whether to print values in raw form.
show print repeats -- Show threshold for repeated print elements.
show print sevenbit-strings -- Show printing of 8-bit characters in strings as \nnn.
show print static-members -- Show printing of C++ static members.
show print symbol -- Show printing of symbol names when printing pointers.
show print symbol-filename -- Show printing of source filename and line number with <SYMBOL>.
show print symbol-loading -- Show printing of symbol loading messages.
show print thread-events -- Show printing of thread events (such as thread start and exit).
show print type -- Generic command for setting how types print.
show print type hex -- Show whether sizes and offsets of struct members are printed using hex notation.
show print type methods -- Show printing of methods defined in classes.
show print type nested-type-limit -- Show the number of recursive nested type definitions to print.
show print type typedefs -- Show printing of typedefs defined in classes.
show print union -- Show printing of unions interior to structures.
show print vtbl -- Show printing of C++ virtual function tables.
show prompt -- Show gdb's prompt.
show prompt-alive-color -- Show prompt alive color.
show prompt-color -- Show prompt color.
show prop-name-color -- Show color used to highlight the name in name-value pairs.
show prop-title-color -- Show color used to highlight the title of name-value pair groups.
show prop-value-color -- Show color used to highlight the value in name-value pairs.
show python -- Prefix command for python preference settings.
show python dont-write-bytecode -- Show whether the Python interpreter should avoid byte-compiling python modules.
show python ignore-environment -- Show whether the Python interpreter showlist ignore environment variables.
show python print-stack -- Show the mode of Python stack printing on error.
show radix -- Show the default input and output number radices.
show range-stepping -- Show whether target-assisted range stepping is enabled.
show ravenscar -- Prefix command for showing Ravenscar-specific settings.
show ravenscar task-switching -- Show whether support for GNAT Ravenscar tasks is enabled.
show record, show rec -- Show record options.
show record btrace -- Show record options.
show record btrace bts -- Show record btrace bts options.
show record btrace bts buffer-size -- Show the record/replay bts buffer size.
show record btrace cpu -- Show the cpu to be used for trace decode.
show record btrace pt -- Show record btrace pt options.
show record btrace pt buffer-size -- Show the record/replay pt buffer size.
show record btrace replay-memory-access -- Show what memory accesses are allowed during replay.
show record full -- Show record options.
show record full insn-number-max -- Show record/replay buffer limit.
show record full memory-query -- Show whether query if PREC cannot record memory change of next instruction.
show record full stop-at-limit -- Show whether record/replay stops when record/replay buffer becomes full.
show record function-call-history-size -- Show number of functions to print in "record function-call-history".
show record instruction-history-size -- Show number of instructions to print in "record instruction-history".
show remote -- Remote protocol specific variables.
show remote TracepointSource-packet -- Show current use of remote protocol `TracepointSource' (TracepointSource) packet.
show remote Z-packet -- Show use of remote protocol `Z' packets.
show remote access-watchpoint-packet -- Show current use of remote protocol `Z4' (access-watchpoint) packet.
show remote agent-packet -- Show current use of remote protocol `QAgent' (agent) packet.
show remote allow-packet -- Show current use of remote protocol `QAllow' (allow) packet.
show remote attach-packet -- Show current use of remote protocol `vAttach' (attach) packet.
show remote binary-download-packet, 
   show remote X-packet -- Show current use of remote protocol `X' (binary-download) packet.
show remote breakpoint-commands-packet -- Show current use of remote protocol `BreakpointCommands' (breakpoint-commands) packet.
show remote btrace-conf-bts-size-packet -- Show current use of remote protocol `Qbtrace-conf:bts:size' (btrace-conf-bts-size) packet.
show remote btrace-conf-pt-size-packet -- Show current use of remote protocol `Qbtrace-conf:pt:size' (btrace-conf-pt-size) packet.
show remote catch-syscalls-packet -- Show current use of remote protocol `QCatchSyscalls' (catch-syscalls) packet.
show remote conditional-breakpoints-packet -- Show current use of remote protocol `ConditionalBreakpoints' (conditional-breakpoints) packet.
show remote conditional-tracepoints-packet -- Show current use of remote protocol `ConditionalTracepoints' (conditional-tracepoints) packet.
show remote ctrl-c-packet -- Show current use of remote protocol `vCtrlC' (ctrl-c) packet.
show remote disable-btrace-packet -- Show current use of remote protocol `Qbtrace:off' (disable-btrace) packet.
show remote disable-randomization-packet -- Show current use of remote protocol `QDisableRandomization' (disable-randomization) packet.
show remote enable-btrace-bts-packet -- Show current use of remote protocol `Qbtrace:bts' (enable-btrace-bts) packet.
show remote enable-btrace-pt-packet -- Show current use of remote protocol `Qbtrace:pt' (enable-btrace-pt) packet.
show remote environment-hex-encoded-packet -- Show current use of remote protocol `QEnvironmentHexEncoded' (environment-hex-encoded) packet.
show remote environment-reset-packet -- Show current use of remote protocol `QEnvironmentReset' (environment-reset) packet.
show remote environment-unset-packet -- Show current use of remote protocol `QEnvironmentUnset' (environment-unset) packet.
show remote exec-event-feature-packet -- Show current use of remote protocol `exec-event-feature' (exec-event-feature) packet.
show remote exec-file -- Show the remote pathname for "run".
show remote fast-tracepoints-packet -- Show current use of remote protocol `FastTracepoints' (fast-tracepoints) packet.
show remote fetch-register-packet, 
   show remote p-packet -- Show current use of remote protocol `p' (fetch-register) packet.
show remote fork-event-feature-packet -- Show current use of remote protocol `fork-event-feature' (fork-event-feature) packet.
show remote get-thread-information-block-address-packet -- Show current use of remote protocol `qGetTIBAddr' (get-thread-information-block-address) packet.
show remote get-thread-local-storage-address-packet -- Show current use of remote protocol `qGetTLSAddr' (get-thread-local-storage-address) packet.
show remote hardware-breakpoint-limit -- Show the maximum number of target hardware breakpoints.
show remote hardware-breakpoint-packet -- Show current use of remote protocol `Z1' (hardware-breakpoint) packet.
show remote hardware-watchpoint-length-limit -- Show the maximum length (in bytes) of a target hardware watchpoint.
show remote hardware-watchpoint-limit -- Show the maximum number of target hardware watchpoints.
show remote hostio-close-packet -- Show current use of remote protocol `vFile:close' (hostio-close) packet.
show remote hostio-fstat-packet -- Show current use of remote protocol `vFile:fstat' (hostio-fstat) packet.
show remote hostio-open-packet -- Show current use of remote protocol `vFile:open' (hostio-open) packet.
show remote hostio-pread-packet -- Show current use of remote protocol `vFile:pread' (hostio-pread) packet.
show remote hostio-pwrite-packet -- Show current use of remote protocol `vFile:pwrite' (hostio-pwrite) packet.
show remote hostio-readlink-packet -- Show current use of remote protocol `vFile:readlink' (hostio-readlink) packet.
show remote hostio-setfs-packet -- Show current use of remote protocol `vFile:setfs' (hostio-setfs) packet.
show remote hostio-unlink-packet -- Show current use of remote protocol `vFile:unlink' (hostio-unlink) packet.
show remote hwbreak-feature-packet -- Show current use of remote protocol `hwbreak-feature' (hwbreak-feature) packet.
show remote install-in-trace-packet -- Show current use of remote protocol `InstallInTrace' (install-in-trace) packet.
show remote interrupt-on-connect -- Show whether interrupt-sequence is sent to remote target when gdb connects to.
show remote interrupt-sequence -- Show interrupt sequence to remote target.
show remote kill-packet -- Show current use of remote protocol `vKill' (kill) packet.
show remote library-info-packet -- Show current use of remote protocol `qXfer:libraries:read' (library-info) packet.
show remote library-info-svr4-packet -- Show current use of remote protocol `qXfer:libraries-svr4:read' (library-info-svr4) packet.
show remote memory-map-packet -- Show current use of remote protocol `qXfer:memory-map:read' (memory-map) packet.
show remote memory-read-packet-size -- Show the maximum number of bytes per memory-read packet.
show remote memory-tagging-feature-packet -- Show current use of remote protocol `memory-tagging-feature' (memory-tagging-feature) packet.
show remote memory-write-packet-size -- Show the maximum number of bytes per memory-write packet.
show remote multiprocess-feature-packet -- Show current use of remote protocol `multiprocess-feature' (multiprocess-feature) packet.
show remote no-resumed-stop-reply-packet -- Show current use of remote protocol `N stop reply' (no-resumed-stop-reply) packet.
show remote noack-packet -- Show current use of remote protocol `QStartNoAckMode' (noack) packet.
show remote osdata-packet -- Show current use of remote protocol `qXfer:osdata:read' (osdata) packet.
show remote pass-signals-packet -- Show current use of remote protocol `QPassSignals' (pass-signals) packet.
show remote pid-to-exec-file-packet -- Show current use of remote protocol `qXfer:exec-file:read' (pid-to-exec-file) packet.
show remote program-signals-packet -- Show current use of remote protocol `QProgramSignals' (program-signals) packet.
show remote query-attached-packet -- Show current use of remote protocol `qAttached' (query-attached) packet.
show remote read-aux-vector-packet -- Show current use of remote protocol `qXfer:auxv:read' (read-aux-vector) packet.
show remote read-btrace-conf-packet -- Show current use of remote protocol `qXfer:btrace-conf' (read-btrace-conf) packet.
show remote read-btrace-packet -- Show current use of remote protocol `qXfer:btrace' (read-btrace) packet.
show remote read-fdpic-loadmap-packet -- Show current use of remote protocol `qXfer:fdpic:read' (read-fdpic-loadmap) packet.
show remote read-sdata-object-packet -- Show current use of remote protocol `qXfer:statictrace:read' (read-sdata-object) packet.
show remote read-siginfo-object-packet -- Show current use of remote protocol `qXfer:siginfo:read' (read-siginfo-object) packet.
show remote read-watchpoint-packet -- Show current use of remote protocol `Z3' (read-watchpoint) packet.
show remote reverse-continue-packet -- Show current use of remote protocol `bc' (reverse-continue) packet.
show remote reverse-step-packet -- Show current use of remote protocol `bs' (reverse-step) packet.
show remote run-packet -- Show current use of remote protocol `vRun' (run) packet.
show remote search-memory-packet -- Show current use of remote protocol `qSearch:memory' (search-memory) packet.
show remote set-register-packet, 
   show remote P-packet -- Show current use of remote protocol `P' (set-register) packet.
show remote set-working-dir-packet -- Show current use of remote protocol `QSetWorkingDir' (set-working-dir) packet.
show remote software-breakpoint-packet -- Show current use of remote protocol `Z0' (software-breakpoint) packet.
show remote startup-with-shell-packet -- Show current use of remote protocol `QStartupWithShell' (startup-with-shell) packet.
show remote static-tracepoints-packet -- Show current use of remote protocol `StaticTracepoints' (static-tracepoints) packet.
show remote supported-packets-packet -- Show current use of remote protocol `qSupported' (supported-packets) packet.
show remote swbreak-feature-packet -- Show current use of remote protocol `swbreak-feature' (swbreak-feature) packet.
show remote symbol-lookup-packet -- Show current use of remote protocol `qSymbol' (symbol-lookup) packet.
show remote system-call-allowed -- Show if the host system(3) call is allowed for the target.
show remote target-features-packet -- Show current use of remote protocol `qXfer:features:read' (target-features) packet.
show remote thread-events-packet -- Show current use of remote protocol `QThreadEvents' (thread-events) packet.
show remote thread-options-packet -- Show current use of remote protocol `QThreadOptions' (thread-options) packet.
show remote threads-packet -- Show current use of remote protocol `qXfer:threads:read' (threads) packet.
show remote trace-buffer-size-packet -- Show current use of remote protocol `QTBuffer:size' (trace-buffer-size) packet.
show remote trace-status-packet -- Show current use of remote protocol `qTStatus' (trace-status) packet.
show remote traceframe-info-packet -- Show current use of remote protocol `qXfer:traceframe-info:read' (traceframe-info) packet.
show remote unwind-info-block-packet -- Show current use of remote protocol `qXfer:uib:read' (unwind-info-block) packet.
show remote verbose-resume-packet -- Show current use of remote protocol `vCont' (verbose-resume) packet.
show remote verbose-resume-supported-packet -- Show current use of remote protocol `vContSupported' (verbose-resume-supported) packet.
show remote vfork-event-feature-packet -- Show current use of remote protocol `vfork-event-feature' (vfork-event-feature) packet.
show remote write-siginfo-object-packet -- Show current use of remote protocol `qXfer:siginfo:write' (write-siginfo-object) packet.
show remote write-watchpoint-packet -- Show current use of remote protocol `Z2' (write-watchpoint) packet.
show remoteaddresssize -- Show the maximum size of the address (in bits) in a memory packet.
show remotecache -- Show cache use for remote targets.
show remoteflow -- Show use of hardware flow control for remote serial I/O.
show remotelogbase -- Show numerical base for remote session logging.
show remotelogfile -- Show filename for remote session recording.
show remotetimeout -- Show timeout limit to wait for target to respond.
show remotewritesize -- Show the maximum number of bytes per memory write packet (deprecated).
show resolve-heap-via-heuristic -- Show the strategy to resolve heap via heuristic.
show safe-linking -- Show whether glibc uses safe-linking.
show schedule-multiple -- Show mode for resuming threads of all processes.
show scheduler-locking -- Show mode for locking scheduler during execution.
show script-extension -- Show mode for script filename extension recognition.
show serial -- Show default serial/parallel port configuration.
show serial baud -- Show baud rate for remote serial I/O.
show serial parity -- Show parity for remote serial I/O.
show show-compact-regs -- Show whether to show a compact register view with columns.
show show-compact-regs-columns -- Show the number of columns (0 for dynamic number of columns).
show show-compact-regs-min-width -- Show the minimum width of each column.
show show-compact-regs-separation -- Show the number of spaces separating columns.
show show-flags -- Show whether to show flags registers.
show show-retaddr-reg -- Show whether to show return address register.
show show-tips -- Show whether to display the tip of the day on startup.
show solib-search-path -- Show the search path for loading non-absolute shared library symbol files.
show source -- Generic command for showing source settings.
show source open -- Show whether GDB should open source files.
show stack-cache -- Show cache use for stack access.
show startup-quietly -- 		Show whether GDB should start up quietly.
show startup-with-shell -- Show use of shell to start subprocesses.
show step-mode -- Show mode of the step operation.
show stop-on-solib-events -- Show stopping for shared library events.
show struct-convention -- Show the convention for returning small structs.
show style -- Style-specific settings.
show style address, show style disassembler address -- Address display styling.
show style address background -- Show the background color for this property.
show style address foreground -- Show the foreground color for this property.
show style address intensity -- Show the display intensity for this property.
show style disassembler -- Style-specific settings for the disassembler.
show style disassembler comment -- Disassembler comment display styling.
show style disassembler comment background -- Show the background color for this property.
show style disassembler comment foreground -- Show the foreground color for this property.
show style disassembler comment intensity -- Show the display intensity for this property.
show style disassembler enabled -- Show whether disassembler output styling is enabled.
show style disassembler immediate -- Disassembler immediate display styling.
show style disassembler immediate background -- Show the background color for this property.
show style disassembler immediate foreground -- Show the foreground color for this property.
show style disassembler immediate intensity -- Show the display intensity for this property.
show style disassembler mnemonic -- Disassembler mnemonic display styling.
show style disassembler mnemonic background -- Show the background color for this property.
show style disassembler mnemonic foreground -- Show the foreground color for this property.
show style disassembler mnemonic intensity -- Show the display intensity for this property.
show style disassembler register -- Disassembler register display styling.
show style disassembler register background -- Show the background color for this property.
show style disassembler register foreground -- Show the foreground color for this property.
show style disassembler register intensity -- Show the display intensity for this property.
show style enabled -- Show whether CLI is enabled.
show style filename -- Filename display styling.
show style filename background -- Show the background color for this property.
show style filename foreground -- Show the foreground color for this property.
show style filename intensity -- Show the display intensity for this property.
show style function, show style disassembler symbol -- Function name display styling.
show style function background -- Show the background color for this property.
show style function foreground -- Show the foreground color for this property.
show style function intensity -- Show the display intensity for this property.
show style highlight -- Highlight display styling.
show style highlight background -- Show the background color for this property.
show style highlight foreground -- Show the foreground color for this property.
show style highlight intensity -- Show the display intensity for this property.
show style metadata -- Metadata display styling.
show style metadata background -- Show the background color for this property.
show style metadata foreground -- Show the foreground color for this property.
show style metadata intensity -- Show the display intensity for this property.
show style sources -- Show whether source code styling is enabled.
show style title -- Title display styling.
show style title background -- Show the background color for this property.
show style title foreground -- Show the foreground color for this property.
show style title intensity -- Show the display intensity for this property.
show style tui-active-border -- TUI active border display styling.
show style tui-active-border background -- Show the background color for this property.
show style tui-active-border foreground -- Show the foreground color for this property.
show style tui-border -- TUI border display styling.
show style tui-border background -- Show the background color for this property.
show style tui-border foreground -- Show the foreground color for this property.
show style tui-current-position -- Show whether to style text highlighted by the TUI's current position indicator.
show style variable -- Variable name display styling.
show style variable background -- Show the background color for this property.
show style variable foreground -- Show the foreground color for this property.
show style variable intensity -- Show the display intensity for this property.
show style version -- Version string display styling.
show style version background -- Show the background color for this property.
show style version foreground -- Show the foreground color for this property.
show style version intensity -- Show the display intensity for this property.
show substitute-path -- Show one or all substitution rules rewriting the source directories.
show suppress-cli-notifications -- Show whether printing notifications on CLI is suppressed.
show syntax-highlight -- Show source code / assembly syntax highlight.
show syntax-highlight-style -- Show source code / assembly syntax highlight stylename of pygments module.
show sysroot, show solib-absolute-prefix -- Show the current system root.
show target-charset -- Show the target character set.
show target-file-system-kind -- Show assumed file system kind for target reported file names.
show target-wide-charset -- Show the target wide character set.
show tcache -- Show the address pointed by tcache.
show tcp -- TCP protocol specific variables.
show tcp auto-retry -- Show auto-retry on socket connect.
show tcp connect-timeout -- Show timeout limit in seconds for socket connection.
show tdesc -- Show target description specific variables.
show tdesc filename -- Show the file to read for an XML target description.
show telescope-dont-skip-registers -- Show don't skip a repeated line if a registers points to it.
show telescope-frame-print-retaddr -- Show print one pointer past the stack frame.
show telescope-framepointer-offset -- Show print offset to framepointer for each address, if sufficiently small.
show telescope-lines -- Show number of lines to printed by the telescope command.
show telescope-offset-color -- Show color of the telescope command (offset prefix).
show telescope-offset-delimiter -- Show offset delimiter of the telescope command.
show telescope-offset-delimiter-color -- Show color of the telescope command (offset delimiter).
show telescope-offset-separator -- Show offset separator of the telescope command.
show telescope-offset-separator-color -- Show color of the telescope command (offset separator).
show telescope-register-color -- Show color of the telescope command (register).
show telescope-repeating-marker -- Show repeating values marker of the telescope command.
show telescope-repeating-marker-color -- Show color of the telescope command (repeating values marker).
show telescope-skip-repeating-val -- Show whether to skip repeating values of the telescope command.
show telescope-skip-repeating-val-min -- Show minimum amount of repeated values before skipping lines.
show thread-arena -- Show the address pointed by thread_arena.
show trace-buffer-size -- Show requested size of trace buffer.
show trace-commands -- Show state of GDB CLI command tracing.
show trace-notes -- Show the notes string to use for current and future trace runs.
show trace-stop-notes -- Show the notes string to use for future tstop commands.
show trace-user -- Show the user name to use for current and future trace runs.
show trust-readonly-sections -- Show mode for reading from readonly sections.
show tui -- TUI configuration variables.
show tui active-border-mode -- Show the attribute mode to use for the active TUI window border.
show tui border-kind -- Show the kind of border for TUI windows.
show tui border-mode -- Show the attribute mode to use for the TUI window borders.
show tui compact-source -- Show whether the TUI source window is compact.
show tui mouse-events -- Show whether TUI mode handles mouse clicks.
show tui tab-width -- Show the tab width, in characters, for the TUI.
show unwind-on-signal, 
   show unwindonsignal -- Show unwinding of stack if a signal is received while in a call dummy.
show unwind-on-terminating-exception -- Show unwinding of stack if std::terminate() is called while in a call dummy.
show unwind-on-timeout -- Show unwinding of stack if a timeout occurs while in a call dummy.
show use-coredump-filter -- Show whether gcore should consider /proc/PID/coredump_filter.
show use-deprecated-index-sections -- Show whether to use deprecated gdb_index sections.
show user -- Show definitions of non-python/scheme user defined commands.
show values -- Elements of value history around item number IDX (or last ten).
show varsize-limit -- Show the maximum number of bytes allowed in a variable-size object.
show verbose -- Show verbosity.
show version -- Show what version of GDB this is.
show vmmap-prefer-relpaths -- Show show relative paths by default in vmmap.
show warranty -- Various kinds of warranty you do not have.
show watchdog -- Show watchdog timer.
show width -- Show number of characters where GDB should wrap lines of its output.
show write -- Show writing into executable and core files.

Command class: support

add-auto-load-safe-path -- Add entries to the list of directories from which it is safe to auto-load files.
add-auto-load-scripts-directory -- Add entries to the list of directories from which to load auto-loaded scripts.
alias -- Define a new command that is an alias of an existing command.
apropos -- Search for commands matching a REGEXP.
define -- Define a new command name.  Command name is argument.
define-prefix -- Define or mark a command as a user-defined prefix command.
demangle -- Demangle a mangled name.
document -- Document a user-defined command or user-defined alias.
dont-repeat -- Don't repeat this command.
down-silently -- Same as the `down' command, but does not print anything.
echo -- Print a constant string.  Give string as argument.
help, h -- Print list of commands.
if -- Execute nested commands once IF the conditional expression is non zero.
interpreter-exec -- Execute a command in an interpreter.
make -- Run the ``make'' program using the rest of the line as arguments.
new-ui -- Create a new UI.
overlay, ov, ovly -- Commands for debugging overlays.
overlay auto -- Enable automatic overlay debugging.
overlay list-overlays -- List mappings of overlay sections.
overlay load-target -- Read the overlay mapping state from the target.
overlay manual -- Enable overlay debugging.
overlay map-overlay -- Assert that an overlay section is mapped.
overlay off -- Disable overlay debugging.
overlay unmap-overlay -- Assert that an overlay section is unmapped.
pipe, | -- Send the output of a gdb command to a shell command.
quit, exit, q -- Exit gdb.
shell, ! -- Execute the rest of the line as a shell command.
source -- Read commands from a file named FILE.
up-silently -- Same as the `up' command, but does not print anything.
while -- Execute nested commands WHILE the conditional expression is non zero.

Command class: text-user-interface

+ -- Scroll window forward.
- -- Scroll window backward.
< -- Scroll window text to the left.
> -- Scroll window text to the right.
> tui -- Text User Interface commands.
> tui disable -- Disable TUI display mode.
> tui enable -- Enable TUI display mode.
> tui focus, fs, focus -- Set focus to named window or next/prev window.
> tui layout, layout -- Change the layout of windows.
> tui layout asm -- Apply the "asm" layout.
> tui layout next -- Apply the next TUI layout.
> tui layout prev -- Apply the previous TUI layout.
> tui layout pwndbg -- Apply the "pwndbg" layout.
> tui layout pwndbg_code -- Apply the "pwndbg_code" layout.
> tui layout regs -- Apply the TUI register layout.
> tui layout split -- Apply the "split" layout.
> tui layout src -- Apply the "src" layout.
> tui new-layout -- Create a new TUI layout.
> tui refresh, refresh -- Refresh the terminal display.
> tui reg -- TUI command to control the register window.
> tui window -- Text User Interface window commands.
> tui window height, wh, winheight -- Set or modify the height of a specified window.
> tui window width, winwidth -- Set or modify the width of a specified window.
> update -- Update the source window to display the current execution point.

Command class: tracepoints

actions -- Specify the actions to be taken at a tracepoint.
collect -- Specify one or more data items to be collected at a tracepoint.
end -- Ends a list of commands or actions.
passcount -- Set the passcount for a tracepoint.
tdump -- Print everything collected at the current tracepoint.
teval -- Specify one or more expressions to be evaluated at a tracepoint.
tfind -- Select a trace frame.
tfind end, tfind none -- De-select any trace frame and resume 'live' debugging.
tfind line -- Select a trace frame by source line.
tfind outside -- Select a trace frame whose PC is outside the given range (exclusive).
tfind pc -- Select a trace frame by PC.
tfind range -- Select a trace frame whose PC is in the given range (inclusive).
tfind start -- Select the first trace frame in the trace buffer.
tfind tracepoint -- Select a trace frame by tracepoint number.
tsave -- Save the trace data to a file.
tstart -- Start trace data collection.
tstatus -- Display the status of the current trace data collection.
tstop -- Stop trace data collection.
tvariable -- Define a trace state variable.
while-stepping, stepping, ws -- Specify single-stepping behavior at a tracepoint.

Command class: user-defined

address -- usage: vmmap [-h] [-w] [-x] [-s] [-A LINES_AFTER] [-B LINES_BEFORE] [-C CONTEXT] [--gaps]
ai -- usage: ai [-h] [-M MODEL] [-t TEMPERATURE] [-m MAX_TOKENS] [-v] [-L] [-c COMMAND] [question ...]
arena -- usage: arena [-h] [addr]
arenas -- usage: arenas [-h]
argc -- usage: argc [-h]
args -- usage: dumpargs [-h] [-f]
argv -- usage: argv [-h] [i]
aslr -- usage: aslr [-h] [{on,off}]
asm -- usage: asm [-h] [-f {hex,string}]
attachp -- usage: attachp [-h] [--no-truncate] [--retry] [--user USER] [-e] [-a] [target]
auxv -- usage: auxv [-h]
auxv-explore -- usage: auxv-explore [-h]
bc -- usage: bc [-h] [which]
bd -- usage: bd [-h] [which]
be -- usage: be [-h] [which]
binder -- usage: binder [-h]
bins -- usage: bins [-h] [addr] [tcache_addr]
bl -- usage: bl [-h]
bn-sync -- usage: bn-sync [-h]
bns -- usage: bn-sync [-h]
bp -- usage: bp [-h] where
break-if-not-taken -- usage: break-if-not-taken [-h] branch
break-if-taken -- usage: break-if-taken [-h] branch
breakrva -- usage: breakrva [-h] [offset] [module]
brva -- usage: breakrva [-h] [offset] [module]
buddydump -- usage: buddydump [-h] [-z ZONE] [-o ORDER] [-m MTYPE] [-p] [-c CPU] [-n NODE] [-f FIND]
bugreport -- usage: bugreport [-h] [--run-browser | --use-gh]
canary -- usage: canary [-h] [-a]
checksec -- usage: checksec [-h] [-f FILE]
comm -- usage: comm [-h] [--addr address] comment
commpage -- usage: commpage [-h] [-v]
config -- usage: config [-h] [filter_pattern]
configfile -- usage: configfile [-h] [--show-all]
context -- usage: context [-h] [--on] [--off] [subcontext ...]
contextnext -- usage: contextnext [-h] [count]
contextoutput -- usage: contextoutput [-h] section path clearing [banner] [width]
contextprev -- usage: contextprev [-h] [count]
contextsearch -- usage: contextsearch [-h] needle [section]
contextunwatch -- usage: contextunwatch [-h] num
contextwatch -- usage: contextwatch [-h] [{eval,execute}] expression
cpsr -- usage: cpsr [-h] [cpsr_value]
ctx -- usage: context [-h] [--on] [--off] [subcontext ...]
ctx-out -- usage: contextoutput [-h] section path clearing [banner] [width]
ctx-unwatch -- usage: contextunwatch [-h] num
ctx-watch -- usage: contextwatch [-h] [{eval,execute}] expression
ctxn -- usage: contextnext [-h] [count]
ctxp -- usage: contextprev [-h] [count]
ctxsearch -- usage: contextsearch [-h] needle [section]
cunwatch -- usage: contextunwatch [-h] num
cwatch -- usage: contextwatch [-h] [{eval,execute}] expression
cyclic -- usage: cyclic [-h] [-a charset] [-n length] [-t seconds] [-l lookup_value | -d | count] [filename]
cymbol -- usage: cymbol [-h] {add,remove,edit,load,show,file,show-all} ...
da -- usage: da [-h] address [max]
db -- usage: db [-h] address [count]
dc -- usage: dc [-h] address [count]
dd -- usage: dd [-h] address [count]
dds -- usage: dds [-h] addr
decomp -- usage: decomp [-h] [addr] [lines]
dev-dump-instruction -- usage: dev-dump-instruction [-h] [-e] [-n] [address]
distance -- usage: distance [-h] a [b]
do -- usage: down [-h] [n]
dow -- usage: down [-h] [n]
down -- usage: down [-h] [n]
dps -- usage: dds [-h] addr
dq -- usage: dq [-h] address [count]
dqs -- usage: dds [-h] addr
ds -- usage: ds [-h] address [max]
dt -- usage: dt [-h] typename [address]
dump-register-frame -- usage: dump-register-frame [-h] [-p] {armcm-exception,armcm-exception2} [address]
dumpargs -- usage: dumpargs [-h] [-f]
dw -- usage: dw [-h] address [count]
eb -- usage: eb [-h] address [data ...]
ed -- usage: ed [-h] address [data ...]
elfsections -- usage: elfsections [-h] [-R]
emulate -- usage: emulate [-h] [-r REVERSE] [-t TOTAL] [pc] [lines]
entry -- usage: entry [-h] [args ...]
env -- usage: envp [-h] [name]
environ -- usage: envp [-h] [name]
envp -- usage: envp [-h] [name]
eq -- usage: eq [-h] address [data ...]
errno -- usage: errno [-h] [err]
ew -- usage: ew [-h] address [data ...]
ez -- usage: ez [-h] address data
eza -- usage: eza [-h] address data
fastbins -- usage: fastbins [-h] [-v] [addr]
find-fake-fast -- usage: find-fake-fast [-h] [--align] [--glibc-fastbin-bug] [--partial-overwrite]
flag -- usage: setflag [-h] flag value
fsbase -- usage: fsbase [-h]
gdt -- usage: gdt [-h] address [count]
getfile -- usage: getfile [-h]
getpid -- usage: pid [-h]
ghidra -- usage: ghidra [-h] [func]
go -- usage: go [-h]
go-dump -- usage: go-dump [-h] [-x] [-f [DECIMALS]] [-d] [-p] ty address
go-type -- usage: go-type [-h] address
god -- usage: go-dump [-h] [-x] [-f [DECIMALS]] [-d] [-p] ty address
got -- usage: got [-h] [-p PATH_FILTER | -a] [-r] [symbol_filter]
gotplt -- usage: gotplt [-h]
goty -- usage: go-type [-h] address
gsbase -- usage: gsbase [-h]
heap -- usage: heap [-h] [-v] [-s] [addr]
heap-config -- usage: heap-config [-h] [filter_pattern]
hex2ptr -- usage: hex2ptr [-h] hex_string
hexdump -- usage: hexdump [-h] [-C [{py,c}]] [address] [count]
hi -- usage: hi [-h] [-v] [-s] [-f] addr
hijack-fd -- usage: hijack-fd [-h] fdnum newfile
ignore -- usage: ignore [-h] [N] COUNT
init -- usage: start [-h] [args ...]
ipi -- usage: ipi [-h]
j -- usage: j [-h]
jemalloc-extent-info -- usage: jemalloc-extent-info [-h] [-v] addr
jemalloc-find-extent -- usage: jemalloc-find-extent [-h] addr
jemalloc-heap -- usage: jemalloc-heap [-h]
k -- usage: k [-h]
kallsyms -- usage: klookup [-h] [-a] [symbol]
kbase -- usage: kbase [-h] [-r] [-v]
kbpf -- usage: kbpf [-h] [-v] [-p] [-m]
kchecksec -- usage: kchecksec [-h]
kcmdline -- usage: kcmdline [-h]
kconfig -- usage: kconfig [-h] [-l FILE_PATH] [config_name]
kcurrent -- usage: kcurrent [-h] [--set] [pid]
kd -- usage: dds [-h] addr
kdmabuf -- usage: kdmabuf [-h]
kdmesg -- usage: kdmesg [-h] [-T]
kfile -- usage: kfile [-h] [--fd [FD]] [pid]
killthreads -- usage: killthreads [-h] [-a] [thread_ids ...]
klookup -- usage: klookup [-h] [-a] [symbol]
kmem-trace -- usage: kmem-trace [-h] [-s] [-b] [-v] [-c COMMAND] [--all]
kmod -- usage: kmod [-h] [-l PATH] [module_name]
knft-dump -- usage: knft-dump [-h] [nsid]
knft-list-chains -- usage: knft-list-chains [-h] [--nsid NSID] [table_family] [table_name]
knft-list-exprs -- usage: knft-list-exprs [-h] [--nsid NSID] [table_family] [table_name] [chain_name] [rule_id]
knft-list-flowtables -- usage: knft-list-flowtables [-h] [--nsid NSID] [table_family] [table_name]
knft-list-objects -- usage: knft-list-objects [-h] [--nsid NSID] [table_family] [table_name]
knft-list-rules -- usage: knft-list-rules [-h] [--nsid NSID] [table_family] [table_name] [chain_name]
knft-list-sets -- usage: knft-list-sets [-h] [--nsid NSID] [table_family] [table_name]
knft-list-tables -- usage: knft-list-tables [-h] [--nsid NSID]
ks -- usage: klookup [-h] [-a] [symbol]
ksyscalls -- usage: ksyscalls [-h] [syscall_name]
ktask -- usage: ktask [-h] [task_name]
kversion -- usage: kversion [-h]
largebins -- usage: largebins [-h] [-v] [addr]
leakfind -- usage: leakfind [-h] [-p [PAGE_NAME]] [-o [MAX_OFFSET]] [-d [MAX_DEPTH]] [-s [STEP]]
libcinfo -- usage: libcinfo [-h]
libs -- usage: vmmap [-h] [-w] [-x] [-s] [-A LINES_AFTER] [-B LINES_BEFORE] [-C CONTEXT] [--gaps]
linkmap -- usage: linkmap [-h]
lm -- usage: vmmap [-h] [-w] [-x] [-s] [-A LINES_AFTER] [-B LINES_BEFORE] [-C CONTEXT] [--gaps]
ln -- usage: ln [-h] [value]
log-level -- usage: log-level [-h] [{debug,info,warning,error,critical}]
main -- usage: start [-h] [args ...]
malloc-chunk -- usage: malloc-chunk [-h] [-f] [-v] [-s] [-d] [-n NEXT] addr
mallocng-dump -- usage: mallocng-dump [-h] [-ma META_AREA]
mallocng-explain -- usage: mallocng-explain [-h]
mallocng-find -- usage: mallocng-find [-h] [-a] [-m] [-s] address
mallocng-group -- usage: mallocng-group [-h] [-i INDEX] address
mallocng-malloc-context -- usage: mallocng-malloc-context [-h] [address]
mallocng-meta -- usage: mallocng-meta [-h] address
mallocng-meta-area -- usage: mallocng-meta-area [-h] [-i INDEX] address
mallocng-slot-start -- usage: mallocng-slot-start [-h] [-a] address
mallocng-slot-user -- usage: mallocng-slot-user [-h] [-a] address
mallocng-visualize-slots -- usage: mallocng-visualize-slots [-h] address [count]
memfrob -- usage: memfrob [-h] address count
memoize -- usage: memoize [-h]
mmap -- usage: mmap [-h] [--quiet] [--force] addr length [prot] [flags] [fd] [offset]
mp -- usage: mp [-h]
mprotect -- usage: mprotect [-h] addr length prot
msr -- usage: msr [-h] [-w [write_value]] [-l] [-r [MSR_RANGE]] [msr]
nearpc -- usage: nearpc [-h] [-r REVERSE] [-t TOTAL] [-e] [pc] [lines]
nextcall -- usage: nextcall [-h] [symbol_regex]
nextjmp -- usage: nextjmp [-h]
nextjump -- usage: nextjmp [-h]
nextproginstr -- usage: nextproginstr [-h]
nextret -- usage: nextret [-h]
nextsc -- usage: nextsyscall [-h]
nextsyscall -- usage: nextsyscall [-h]
ng-ctx -- usage: mallocng-malloc-context [-h] [address]
ng-dump -- usage: mallocng-dump [-h] [-ma META_AREA]
ng-explain -- usage: mallocng-explain [-h]
ng-find -- usage: mallocng-find [-h] [-a] [-m] [-s] address
ng-group -- usage: mallocng-group [-h] [-i INDEX] address
ng-ma -- usage: mallocng-meta-area [-h] [-i INDEX] address
ng-meta -- usage: mallocng-meta [-h] address
ng-metaarea -- usage: mallocng-meta-area [-h] [-i INDEX] address
ng-slots -- usage: mallocng-slot-start [-h] [-a] address
ng-slotu -- usage: mallocng-slot-user [-h] [-a] address
ng-vis -- usage: mallocng-visualize-slots [-h] address [count]
onegadget -- usage: onegadget [-h] [--show-unsat] [--no-unknown] [-v]
p2p -- usage: p2p [-h] mapping_names [mapping_names ...]
p2v -- usage: p2v [-h] paddr
pageinfo -- usage: pageinfo [-h] page
pagewalk -- usage: pagewalk [-h] [--pgd ENTRY] vaddr
parse-seccomp -- usage: parse-seccomp [-h] addr
patch -- usage: patch [-h] [-q] address ins
patch-list -- usage: patch-list [-h]
patch-revert -- usage: patch-revert [-h] address
pc -- usage: pc [-h]
pdisass -- usage: nearpc [-h] [-r REVERSE] [-t TOTAL] [-e] [pc] [lines]
peb -- usage: peb [-h]
pid -- usage: pid [-h]
piebase -- usage: piebase [-h] [offset] [module]
plist -- usage: plist [-h] [-s SENTINEL] [-i INNER_NAME] [-f FIELD_NAME] [-o OFFSET] [-c COUNT] path next
plt -- usage: plt [-h] [-a]
probeleak -- usage: probeleak [-h] [--max-distance MAX_DISTANCE] [--point-to POINT_TO] [--max-ptrs MAX_PTRS]
procinfo -- usage: procinfo [-h]
profiler -- usage: profiler [-h] {start,stop} ...
pstate -- usage: cpsr [-h] [cpsr_value]
pwndbg -- usage: pwndbg [-h] [-c CATEGORY_ | --list-categories] [filter_pattern]
r2 -- usage: r2 [-h] [--no-seek] [--no-rebase] [arguments ...]
r2pipe -- usage: r2pipe [-h] arguments [arguments ...]
radare2 -- usage: r2 [-h] [--no-seek] [--no-rebase] [arguments ...]
regs -- usage: regs [-h] [regs ...]
reinit-pwndbg -- usage: reinit-pwndbg [-h]
reload -- usage: reload [-h]
retaddr -- usage: retaddr [-h]
rizin -- usage: rz [-h] [--no-seek] [--no-rebase] [arguments ...]
rop -- usage: rop [-h] [--grep GREP] [--memlimit MEMLIMIT] [argument ...]
ropgadget -- usage: rop [-h] [--grep GREP] [--memlimit MEMLIMIT] [argument ...]
ropper -- usage: ropper [-h] [argument ...]
rz -- usage: rz [-h] [--no-seek] [--no-rebase] [arguments ...]
rzpipe -- usage: rzpipe [-h] arguments [arguments ...]
save-ida -- usage: save-ida [-h]
search -- usage: search [-h] [-t {byte,short,word,dword,qword,pointer,string,bytes,asm}] [-1] [-2] [-4] [-8]
setflag -- usage: setflag [-h] flag value
sigreturn -- usage: sigreturn [-h] [-a] [-p] [address]
slab -- usage: slab [-h] {list,info,contains} ...
smallbins -- usage: smallbins [-h] [-v] [addr]
so -- usage: stepover [-h] [addr]
spray -- usage: spray [-h] [--value VALUE] [-x] addr [length]
sstart -- usage: sstart [-h]
stack -- usage: stack [-h] [-f] [-i] [count] [offset]
stack-explore -- usage: stack-explore [-h]
stackf -- usage: stackf [-h] [count] [offset]
start -- usage: start [-h] [args ...]
stepover -- usage: stepover [-h] [addr]
stepret -- usage: stepret [-h]
stepsc -- usage: stepsyscall [-h]
stepsyscall -- usage: stepsyscall [-h]
stepuntilasm -- usage: stepuntilasm [-h] mnemonic [op_str ...]
strings -- usage: strings [-h] [-n N] [--save-as SAVE_AS] [page_names ...]
tcache -- usage: tcache [-h] [addr]
tcachebins -- usage: tcachebins [-h] [-v] [addr]
telescope -- usage: telescope [-h] [-r] [-f] [-i] [address] [count]
theme -- usage: theme [-h] [filter_pattern]
themefile -- usage: themefile [-h] [--show-all]
threads -- usage: threads [-h] [-c] [num_threads]
tips -- usage: tips [-h] [-a]
tls -- usage: tls [-h] [-p] [-a]
top-chunk -- usage: top-chunk [-h] [addr]
track-got -- usage: track-got [-h] {enable,disable,info,query} ...
track-heap -- usage: track-heap [-h] {enable,disable,toggle-break} ...
try-free -- usage: try-free [-h] addr
u -- usage: nearpc [-h] [-r REVERSE] [-t TOTAL] [-e] [pc] [lines]
unsortedbin -- usage: unsortedbin [-h] [-v] [addr]
up -- usage: up [-h] [n]
v2p -- usage: v2p [-h] vaddr
valist -- usage: valist [-h] addr [count]
version -- usage: version [-h]
vis -- usage: vis-heap-chunks [-h] [--beyond_top] [--no_truncate] [--all_chunks] [count] [addr]
vis-heap-chunks -- usage: vis-heap-chunks [-h] [--beyond_top] [--no_truncate] [--all_chunks] [count] [addr]
vmmap -- usage: vmmap [-h] [-w] [-x] [-s] [-A LINES_AFTER] [-B LINES_BEFORE] [-C CONTEXT] [--gaps]
vmmap-add -- usage: vmmap-add [-h] start size [flags] [offset]
vmmap-clear -- usage: vmmap-clear [-h]
vmmap-explore -- usage: vmmap-explore [-h] address
vmmap-load -- usage: vmmap-load [-h] [filename]
vprot -- usage: vmmap [-h] [-w] [-x] [-s] [-A LINES_AFTER] [-B LINES_BEFORE] [-C CONTEXT] [--gaps]
xinfo -- usage: xinfo [-h] [address]
xor -- usage: xor [-h] address key count
xpsr -- usage: cpsr [-h] [cpsr_value]
xuntil -- usage: xuntil [-h] target

Unclassified commands

add-inferior -- Add a new inferior.
clone-inferior -- Clone inferior ID.
eval -- Construct a GDB command and then evaluate it.
flash-erase -- Erase all flash memory regions.
function -- Placeholder command for showing help on convenience functions.
function _any_caller_is -- Check all calling function's names.
function _any_caller_matches -- Compare all calling function's names with a regexp.
function _as_string -- Return the string representation of a value.
function _caller_is -- Check the calling function's name.
function _caller_matches -- Compare the calling function's name with a regexp.
function _cimag -- Extract the imaginary part of a complex number.
function _creal -- Extract the real part of a complex number.
function _gdb_maint_setting -- $_gdb_maint_setting - returns the value of a GDB maintenance setting.
function _gdb_maint_setting_str -- $_gdb_maint_setting_str - returns the value of a GDB maintenance setting as a string.
function _gdb_setting -- $_gdb_setting - returns the value of a GDB setting.
function _gdb_setting_str -- $_gdb_setting_str - returns the value of a GDB setting as a string.
function _isvoid -- Check whether an expression is void.
function _memeq -- $_memeq - compare bytes of memory.
function _regex -- $_regex - check if a string matches a regular expression.
function _shell -- $_shell - execute a shell command and return the result.
function _streq -- $_streq - check string equality.
function _strlen -- $_strlen - compute string length.
function argc -- Get the number of program arguments.
function argv -- Get the n-th program argument.
function base -- Return the base address of the first memory mapping containing the given name.
function bn_eval -- Parse and evaluate a Binary Ninja expression.
function bn_sym -- Lookup a symbol's address by name from Binary Ninja.
function bn_var -- Lookup a stack variable's address by name from Binary Ninja.
function environ -- Get an environment variable by name.
function envp -- Get the n-th environment variable.
function fsbase -- Get the value of the FS segment register.
function gsbase -- Get the value of the GS segment register.
function hex2ptr -- Converts a hex string to a little-endian address and returns the address.
function ida -- Lookup a symbol's address by name from IDA.
function rebase -- Return address rebased onto the executable's mappings.
jit-reader-load -- Load FILE as debug info reader and unwinder for JIT compiled code.
jit-reader-unload -- Unload the currently loaded JIT debug info reader.
remove-inferiors -- Remove inferior ID (or list of IDs).
unset -- Complement to certain "set" commands.
unset environment -- Cancel environment variable VAR for the program.
unset exec-wrapper -- Disable use of an execution wrapper.
unset substitute-path -- Delete one or all substitution rules rewriting the source directories.
unset tdesc -- Unset target description specific variables.
unset tdesc filename -- Unset the file to read for an XML target description.