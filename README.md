### SwiftLintConfigs

My configs of .swiftlint.yml file

```
excluded:
    - Pods
    - Scripts
disabled_rules:
    - trailing_whitespace
    - type_body_length
    - nesting
    - todo
    - notification_center_detachment
    - line_length

opt_in_rules:
    - private_outlet
    - empty_count
    - closing_brace
    - opening_brace
    - trailing_semicolon
    - explicit_init
    - overridden_super_call
    - redundant_nil_coalescing
    - operator_usage_whitespace
    - closure_end_indentation
    - object_literal
    - prohibited_super_call
    - fatal_error_message
    - force_unwrapping

trailing_semicolon: error
colon: error
comma: error
opening_brace: error
closing_brace: error

file_length:
    warning: 800
    error: 1000

warning_threshold: 15

