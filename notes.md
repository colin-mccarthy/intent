

{
    "msg": {
        "msg": "All items completed",
        "changed": true,
        "results": [
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server community ansibull RO 99",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server community ansibull RO 99"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server trap-source Loopback0",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server trap-source Loopback0"
            },
            {
                "_ansible_parsed": true,
                "commands": [
                    "no snmp-server contact noc@google.com"
                ],
                "_ansible_item_result": true,
                "_ansible_no_log": false,
                "failed": false,
                "changed": true,
                "item": "snmp-server contact noc@google.com",
                "updates": [
                    "no snmp-server contact noc@google.com"
                ],
                "invocation": {
                    "module_args": {
                        "multiline_delimiter": "@",
                        "authorize": null,
                        "force": false,
                        "diff_against": null,
                        "replace": "line",
                        "running_config": null,
                        "save_when": "never",
                        "port": null,
                        "before": null,
                        "auth_pass": null,
                        "parents": null,
                        "provider": null,
                        "save": false,
                        "match": "line",
                        "username": null,
                        "defaults": false,
                        "after": null,
                        "host": null,
                        "password": null,
                        "diff_ignore_lines": null,
                        "src": null,
                        "ssh_keyfile": null,
                        "lines": [
                            "no snmp-server contact noc@google.com"
                        ],
                        "intended_config": null,
                        "timeout": null,
                        "backup": false
                    }
                },
                "banners": {},
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server contact noc@google.com"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server enable traps ospf state-change",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server enable traps ospf state-change"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server enable traps ospf errors",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server enable traps ospf errors"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server enable traps ospf retransmit",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server enable traps ospf retransmit"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server enable traps ospf lsa",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server enable traps ospf lsa"
            },
            {
                "skipped": true,
                "_ansible_no_log": false,
                "skip_reason": "Conditional result was False",
                "_ansible_item_result": true,
                "item": "snmp-server host 192.168.161.110 version 2c public udp-port 161",
                "changed": false,
                "_ansible_ignore_errors": null,
                "_ansible_item_label": "snmp-server host 192.168.161.110 version 2c public udp-port 161"
            }
        ]
    },
    "changed": false,
    "_ansible_verbose_always": true,
    "_ansible_no_log": false
}
