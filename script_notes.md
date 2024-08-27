

# Advanced Bash Scripting Review Notes



1. Shell
    
2. Cleanup
   1. a simple log clean-up script
   
            # Cleanup 
            # Run as root of course

            cd /var/log
            cat /dev/null > messages
            cat /dev/null > wtmp
            echo "Log files cleaned up."