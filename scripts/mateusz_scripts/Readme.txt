Warunki wstępne:

# instalacja ze strony NVIDIA sterownika => CUDA 10.1
# pobranie folderu cuDNN (zawierającej trzy biblioteki) ze strony NVIDIA oraz wypakowanie bibliotek do folderu 
gdzie została zainstalowana CUDA => C:\Program Files\NVIDA GPU Computing Toolkit\CUDA\v10.0
# W zmiennych środowiskowych Windowsa sprawdzenie czy pojawiły się ścieżki dla CUDA 
# instalacja TensorFlow w wersji => 2.1.0
# import wszystkich bibliotek widocznych w skryptach

Do odpalenia kodu "Tensorboard SP500.py" Użyj wiersza poleceń, aby zmienić katalog na ścieżkę pliku zgłoszoną przez pwd lub bieżącą lokalizację pliku .py
Następnie uruchom ten kod w wierszu polecenia lub terminalu, wpisując - 'tensorboard --logdir logs\fit'
Tensorboard będzie działał lokalnie w twojej przeglądarce pod adresem http://localhost:6006/

W razie problemów proszę skorzystać z instrukcji na stronie:
https://towardsdatascience.com/installing-tensorflow-with-cuda-cudnn-and-gpu-support-on-windows-10-60693e46e781
