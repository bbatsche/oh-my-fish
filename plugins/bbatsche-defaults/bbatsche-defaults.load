set PATH "."
set PATH $PATH "~/bin"
set PATH $PATH "/opt/local/sbin" "/opt/local/bin"
set PATH $PATH "/usr/local/sbin" "/usr/local/bin"
set PATH $PATH "/usr/sbin" "/usr/bin"
set PATH $PATH "/sbin" "/bin"
set PATH $PATH "$HOME/.composer/vendor/bin"
set PATH $PATH "/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources"

set fish_greeting Type (set_color green)help(set_color normal) for instructions on how to use the fish shell

function la --description 'List contents of directory, including hidden files in directory using long format'
  ls -lAhFG $argv
end

function ll --description 'List contents of directory using long format'
  ls -lhFG $argv
end

function px
    ps xco pid,pcpu,pmem,command
end

function pxa
    ps axco user,pid,pcpu,pmem,command
end

function logout --description 'I am so used to running logout instead of exit. Let\'s just give up already.'
    exit
end

set -g fish_key_bindings fish_vi_key_bindings
