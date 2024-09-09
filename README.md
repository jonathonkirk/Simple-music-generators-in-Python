# Chord Progression Generator

A simple Python program generates a chord progression consisting of major and minor triads, and major and minor seventh chords. The progression is built using a user-defined starting chord, and each subsequent chord must share at least one common tone (note) with the previous chord.

## Features

- Supports major and minor triads (`M` and `m`) and major and minor seventh chords (`M7` and `m7`).
- Chords are named using standard chord symbols (e.g., `C`, `Cm`, `CM7`, `Cm7`).
- The user specifies the root of the starting chord and the length of the progression.
- Supports both sharp (`#`) and flat (`b`) notation for accidentals, automatically converting flats to enharmonic sharps (e.g., `Db` becomes `C#`).

## How It Works

1. The user inputs a starting chord by specifying the root note and chord type.
2. The user specifies the length of the chord progression (number of chords).
3. The program generates a random chord progression where each subsequent chord shares at least one common note with the previous chord.
4. The progression is printed in standard chord symbol notation.

License information

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.


