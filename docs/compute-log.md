# Compute Benchmark Log

## System Information

==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.22631
Machine:    AMD64
Processor:  Intel64 Family 6 Model 165 Stepping 2, GenuineIntel
Python:     3.12.10 (tags/v3.12.10:0cc8128, Apr  8 2025, 12:21:36) [MSC v.1943 64 bit (AMD64)]

## Benchmark Results

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.4087 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.3781 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0779 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.4087s
  list benchmark:   0.3781s
  string benchmark: 0.0779s

## Total RAM

Total RAM: 8 GB