

flutter create .
flutter config --enable-web
flutter run -d chrome


flutter build web
cd build/web
python3 -m http.server 8000

ipconfig getifaddr en0
