Opis projektu (PL)
Cyfrowy miernik SINAD do transceiverów krótkofalarskich

Projekt przedstawia cyfrowy miernik SINAD przeznaczony do pomiaru czułości i jakości toru audio w transceiverach krótkofalarskich (AM / FM / SSB).

Układ oparty jest na mikrokontrolerze STM32G4 i łączy klasyczną metodę pomiaru SINAD (filtry + RMS) z nowoczesnym przetwarzaniem cyfrowym.

Główne cechy projektu:

precyzyjne próbkowanie ADC sterowane timerem (stabilne Fs)

filtracja analogowa (HPF / LPF / anti-aliasing)

cyfrowa filtracja pasmowa oraz notch 1 kHz

obliczanie RMS oraz SINAD bez użycia FFT

wyjście analogowe DAC do sterowania:

miernikiem µA (wskaźnik analogowy)

lub zewnętrznym woltomierzem

architektura zgodna z klasycznymi miernikami laboratoryjnymi (HP / Rohde & Schwarz)

Projekt został zaprojektowany z naciskiem na:

powtarzalność pomiarów

niskie zniekształcenia własne

możliwość kalibracji

prostotę i przejrzystość algorytmów

🇬🇧 Project description (EN)
Digital SINAD meter for amateur radio transceivers

This project implements a digital SINAD meter intended for measuring receiver sensitivity and audio quality in amateur radio transceivers (AM / FM / SSB).

The design is based on an STM32G4 microcontroller and combines the classical SINAD measurement method (filters + RMS) with modern digital signal processing.

Key features:

precise ADC sampling driven by a hardware timer (stable Fs)

analog input filtering (HPF / LPF / anti-aliasing)

digital bandpass filtering and 1 kHz notch filter

RMS and SINAD calculation without FFT

DAC analog output for:

driving an analog µA meter

or an external voltmeter

###architecture consistent with traditional laboratory SINAD meters

The project focuses on:

measurement repeatability

low internal distortion

calibration capability

simple and transparent signal processing algorithms
