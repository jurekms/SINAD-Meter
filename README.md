# Digital SINAD Meter for Amateur Radio Transceivers

## 🇵🇱 Opis projektu

Projekt przedstawia **cyfrowy miernik SINAD** przeznaczony do pomiaru  
**czułości i jakości toru audio** w transceiverach krótkofalarskich  
pracujących w modulacjach **AM / FM / SSB**.

Układ oparty jest na mikrokontrolerze **STM32G4** i łączy klasyczną metodę
pomiaru **SINAD (filtry + RMS)** z nowoczesnym przetwarzaniem cyfrowym.

### Główne cechy projektu
- precyzyjne próbkowanie ADC sterowane **sprzętowym timerem (stabilne Fs)**
- filtracja analogowa (HPF / LPF / anti-aliasing)
- cyfrowa filtracja pasmowa oraz **notch 1 kHz**
- obliczanie **RMS** oraz **SINAD** bez użycia FFT
- wyjście analogowe **DAC** do sterowania:
  - miernikiem µA (wskaźnik analogowy)
  - lub zewnętrznym woltomierzem

Projekt powstał z naciskiem na:
- powtarzalność pomiarów
- niskie zniekształcenia własne
- możliwość kalibracji
- prostotę i przejrzystość algorytmów

---

## 🇬🇧 Project description

This project implements a **digital SINAD meter** intended for measuring  
**receiver sensitivity and audio quality** in amateur radio transceivers  
operating in **AM / FM / SSB** modes.

The design is based on an **STM32G4 microcontroller** and combines the
classical **SINAD measurement method (filters + RMS)** with modern digital
signal processing techniques.

### Key features
- precise ADC sampling driven by a **hardware timer (stable Fs)**
- analog input filtering (HPF / LPF / anti-aliasing)
- digital bandpass filtering and **1 kHz notch filter**
- **RMS and SINAD calculation without FFT**
- analog **DAC output** for driving:
  - an analog µA meter
  - or an external voltmeter

The project focuses on:
- measurement repeatability
- low internal distortion
- calibration capability
- simple and transparent signal processing algorithms
