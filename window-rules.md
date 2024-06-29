window_rules:
  # Command to run. Use `commands` to specify an array of commands to run in sequence.
  - command: "move to workspace 2"
    # Process name to match exactly.
    match_process_name: "chrome"
    # Window title to match exactly.
    match_title: "/.*/"
    # Class name to match exactly.
    match_class_name: "Chrome_WidgetWin_1"
  # To prevent the WM from managing an app, use the "ignore" command.
  - command: "ignore"
    match_process_name: "notepad"