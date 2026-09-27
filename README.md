<img width="487" height="385" alt="image" src="https://github.com/user-attachments/assets/bf0f094e-42a0-4e26-b57d-b896f1de9b38" />
<img width="489" height="378" alt="image" src="https://github.com/user-attachments/assets/73ebff3a-64ce-4267-88fb-198bf4fbb4e7" />
<img width="479" height="379" alt="image" src="https://github.com/user-attachments/assets/2fabdd6a-5f00-4744-bc73-0e297a890c23" />
<img width="487" height="381" alt="image" src="https://github.com/user-attachments/assets/7dbf7f65-68e9-4ebe-9292-0ee0f4fb7c25" />
C:\Users\andre>pake https://www.youtube.com/ --name Youtube
✼ Using existing local icon: C:\Users\andre\AppData\Local\Temp\pake-build-uyvS2j\src-tauri\png\youtube_256.ico
✺ pnpm not available, using npm for package management.
✸ Building app...

> pake-cli@3.17.1 build
> tauri build -c src-tauri\.pake\tauri.conf.json --target x86_64-pc-windows-msvc --features cli-build

        Info Looking up installed tauri packages to check mismatched versions...
   Compiling pake v3.17.1 (C:\Users\andre\AppData\Local\Temp\pake-build-uyvS2j\src-tauri)
warning: unused import: `webview2_com::Microsoft::Web::WebView2::Win32::ICoreWebView2Controller`
  --> src\app\navigation.rs:66:9
   |
66 |     use webview2_com::Microsoft::Web::WebView2::Win32::ICoreWebView2Controller;
   |         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
   |
   = note: `#[warn(unused_imports)]` (part of `#[warn(unused)]`) on by default

warning: `pake` (lib) generated 1 warning (run `cargo fix --lib -p pake` to apply 1 suggestion)
    Finished `release` profile [optimized] target(s) in 6m 53s
       Built application at: C:\Users\andre\AppData\Roaming\npm\node_modules\pake-cli\src-tauri\target\x86_64-pc-windows-msvc\release\pake-youtube.exe
        Info Patching C:\Users\andre\AppData\Roaming\npm\node_modules\pake-cli\src-tauri\target\x86_64-pc-windows-msvc\release\pake-youtube.exe with bundle type information: msi
        Info Target: x64
     Running candle for "C:\\Users\\andre\\AppData\\Roaming\\npm\\node_modules\\pake-cli\\src-tauri\\target\\x86_64-pc-windows-msvc\\release\\wix\\x64\\main.wxs"
     Running light to produce C:\Users\andre\AppData\Roaming\npm\node_modules\pake-cli\src-tauri\target\x86_64-pc-windows-msvc\release\bundle\msi\Youtube_1.0.0_x64_en-US.msi
    Finished 1 bundle at:
        C:\Users\andre\AppData\Roaming\npm\node_modules\pake-cli\src-tauri\target\x86_64-pc-windows-msvc\release\bundle\msi\Youtube_1.0.0_x64_en-US.msi

✔ Build success!
✔ App installer located in C:\Users\andre\Youtube.msi

   ╭───────────────────────────────────────╮
   │                                       │
   │   Update available 3.17.1 → 3.17.2    │
   │    Run npm i -g pake-cli to update    │
   │                                       │
   ╰───────────────────────────────────────╯


C:\Users\andre>
