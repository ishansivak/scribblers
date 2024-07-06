# Embedded Rust
Tock OS - For running multiple ELF binaries (statically linked)


# Cryptography




# std Rust


# GUI
egui
Rocket
Yew
Dioxus



# Misc
Yazi - ⚡️ Blazing Fast Terminal File Manager
gitoxide - Lean git implementation


# RISC-V
rvemu - THIS CAN RUN IN WEB AND IN TERMINAL
spike


# FINAL STACK
<architecture: wasm32 OR risc32 OR risc64 OR x86 OR ARM>
<os: linux OR win OR mac OR tockos OR mobile>
<ui: 32 bit ? cli ELSE gui>
<platform: browser OR mobile OR terminal>
<data storage: gitoxide + saito>
<execution: cargo + saito> (future)
<ui-lib: tui OR Yazi OR gitui>
<apps: ORDER/PAY TYPE READ> (future extensions: rent bikes, maps, audio, video, delivery)





# Thoughts on UI

Type UI has to be simple and clutter free and minimal, therefore stack:
microcontroller (any) -> tock os -> riscv ELF binaries -> [ <saito> || <type> || <pay> || <read> || <arbitrary 32/64 bit binary>
Pay UI has to be simple and clutter free and needlessly pretty to attract customers lol
