```
TASK [debug set_snmp] *****************************************************************************************************************************
ok: [192.168.161.9] => {
    "set_snmp": {
        "changed": true, 
        "msg": "All items completed", 
        "results": [
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server community ansibull RO 99", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server community ansibull RO 99"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server community ansibull RO 99"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server trap-source Loopback0", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server trap-source Loopback0"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server trap-source Loopback0"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server contact noc@yourcompany.com", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "banners": {}, 
                "changed": true, 
                "commands": [
                    "snmp-server contact noc@yourcompany.com"
                ], 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server contact noc@yourcompany.com"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server contact noc@yourcompany.com", 
                "updates": [
                    "snmp-server contact noc@yourcompany.com"
                ]
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server enable traps ospf state-change", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server enable traps ospf state-change"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server enable traps ospf state-change"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server enable traps ospf errors", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server enable traps ospf errors"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server enable traps ospf errors"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server enable traps ospf retransmit", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server enable traps ospf retransmit"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server enable traps ospf retransmit"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server enable traps ospf lsa", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server enable traps ospf lsa"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server enable traps ospf lsa"
            }, 
            {
                "_ansible_ignore_errors": null, 
                "_ansible_item_label": "snmp-server host 192.168.161.110 version 2c public udp-port 161", 
                "_ansible_item_result": true, 
                "_ansible_no_log": false, 
                "_ansible_parsed": true, 
                "changed": false, 
                "failed": false, 
                "invocation": {
                    "module_args": {
                        "after": null, 
                        "auth_pass": null, 
                        "authorize": null, 
                        "backup": false, 
                        "before": null, 
                        "defaults": false, 
                        "diff_against": null, 
                        "diff_ignore_lines": null, 
                        "force": false, 
                        "host": null, 
                        "intended_config": null, 
                        "lines": [
                            "snmp-server host 192.168.161.110 version 2c public udp-port 161"
                        ], 
                        "match": "line", 
                        "multiline_delimiter": "@", 
                        "parents": null, 
                        "password": null, 
                        "port": null, 
                        "provider": null, 
                        "replace": "line", 
                        "running_config": null, 
                        "save": false, 
                        "save_when": "never", 
                        "src": null, 
                        "ssh_keyfile": null, 
                        "timeout": null, 
                        "username": null
                    }
                }, 
                "item": "snmp-server host 192.168.161.110 version 2c public udp-port 161"
            }
        ]
    }
}


```
