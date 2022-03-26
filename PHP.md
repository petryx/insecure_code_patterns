## Insecure Settings php.ini
- display_errors = on
- log_errors = off
- safe_mode = off
- allow_url_fopen = on
- disable_functions = off
- enable_dl = on
- file_uploads = on
- magic_quotes_gpc = off
- open_basedir = "/" 


## OS Command Injection
- shell_exec
- system
- exec
- popen
- passthru 
- proc_open
- pcntl_exec
- eval
- assert
- preg_replace
- create_function
- preg_match
- str_replace

## LFI or RFI
- file_include
- include
- require
- include_once
- require_once
- fwrite
- file_get_contents
- fopen
- glob
- popen
- file
- str_replace('..', '.', $_POST['filename'])
- fputs


## High Risky

- $_GET['xxx']
- $_
- $_POST
- $_REQUEST
- $_SERVER
- $_SESSION
- debug
