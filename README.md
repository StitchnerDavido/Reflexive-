# Reflexive-
Minimalistic Coding Language.
2KB's
Made in United Kingdom 
Easy to learn
# Reflexive syntax:
write("")
release(variablename) = value 
so variable ==, =>, =< value do
    ...
stop
^^ hello i'm an invisible comment
[[I
AM
MULTI
LINE
COMMENT]]
# Reflexive example code
`` Reflexive
release(score) = 101

so score => 100 do
    write("score is equal or more huge than 100!")
stop

so score =< 100 do
    write("score is tinier or equal to 100!")
stop``
should output condition one with some debugging
# How to install
drop the reflexive file in your main shell terminal app directory or if in termux make a folder with reflexive file inside and do `cd /path/to/directory
make
cp reflexive $PREFIX/bin/` this should make it work then make a file with .rfx as extension and working code, go to terminal then run "reflexive [filename].rfx" and the file if correct should work
# Documentary
This was made November 15 2025 on Saturday out of boredom, and made with the full use of DeepSeek AI. The design was 100% by me, coding 100% by DeepSeek.
# Structure
Reflexive was made using ANSI C, uses bytecode, elf binary. This is my first project on this account. Thank you for coming.
# Paradigm
The paradigm is pretty basic. it's just variables and condition.
# File Stuff (ignore Ui element, tables, modules and inputs. they don't work.)
/system/bin/linker
13676358
__libc_init
__cxa_atexit
__register_atfork
/data/data/com.termux/files/usr/bin/../../usr/lib
libdl.so
reflexive>
releasel
Condition: %s %s %s = %s
Usage: reflexive [script.rfx]
DEBUG: Syncing %d tables
define.done
UI Action triggered: %s
Invalid comparison syntax
Unknown opcode: %d
Type mismatch in comparison
variable_lookup_not_implemented
DEBUG: User entered: %s
Executing TRUE branch...
Loading module: %s as %s
Unknown operator: %s
PressAction
dimensions
Error: Could not open file %s
DEBUG: Created table '%s' with %d elements
[unknown]
Android (13624864, +pgo, +bolt, +lto, +mlgo, based on r530567e) clang version 19.0.1 (https://android.googlesource.com/toolchain/llvm-project 97a699bf4812a18fb657c2779f5296a4ab2694d2)
Linker: LLD 20.1.8
clang version 20.1.8
.note.android.ident
.gnu.version
.gnu.version_r
.gnu.hash
.rel.dyn
.relr.dyn
.ARM.exidx
.rel.plt
.data.rel.ro
.dynamic
.got.plt
.relro_padding
.comment
.ARM.attributes
.shstrtab
crtbegin.c
_start_main
fini_array_with_sentinels
call_fini_array
note_android_ident
note_data
note_name
note_end
ndk_version
ndk_build_number
reflexive.c
parser.c
keywords
reflexive_read_input.buffer
variables.c
tables.c
__libc_init
__fini_array_start
__fini_array_end
__atexit_handler_wrapper
__cxa_atexit
__dso_handle
pthread_atfork
__register_atfork
reflexive_init
reflexive_run_prompt
reflexive_run_file
reflexive_free
parse_and_execute
vm_add_constant
vm_add_instruction
vm_execute
reflexive_write_value
create_ast_node
free_ast_node
lexer_init
lexer_next_token
__aeabi_memcpy8
__aeabi_memclr8
get_variable
reflexive_read_input
create_table
reflexive_write_output
table_add_element
set_variable
evaluate_comparison
parse_value_token
is_keyword
create_token
__aeabi_memclr4
__aeabi_memcpy4
reflexive_write_table
variable_exists
remove_local_variables
table_get_element
table_sync_tables
free_table
create_ui_element
set_ui_property
set_ui_action
trigger_ui_action
free_ui_element
__aeabi_memcpy
__aeabi_memset
__aeabi_memset4
__aeabi_memset8
__aeabi_memclr
_DYNAMIC
# Implementation
If you want to implement Reflexive into a terminal, make sure you first correctly installed it. Then, code the trigger in bash with an extension of `.sh`. Make sure you do chmod +x ./filename.sh (replace filename with your actual file name with .sh extension at the end) check if the bash code works correctly. After all that, do `bash filename.sh` and if the code works it should call your reflexive file (after the first chunk in your bash code, type `reflexive filename.rfx` that has reflexive code inside) so that when bash is called the bash also calls your reflexive file.
