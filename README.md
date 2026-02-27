## Acoustic Analysis: 'Here Comes the Sun' (The Beatles)

This project analyses the acoustic features and structure of 'Here Comes the Sun' to visualize how its musical "vibe" is constructed.

### 1. Acoustic Features Over Time (Chromagram & Cepstrogram)

The **chromagram** visualises the harmonic content of the track over time. Instead of static blocks, we can clearly see the active, rhythmic strumming of the acoustic guitar. There is a distinct structural shift visible: the outer sections (frames 0-80 and 140-200) feature a repeating 3-chord progression. In the middle section (frames 80-140), the harmony shifts and becomes denser, representing the chorus/bridge. 

The **cepstrogram (MFCCs)** captures the timbral texture. The vertical striations represent rhythmic transients (drum hits and picking). You can observe a textural shift in the middle section where the coefficients change noticeably, representing the instrumentation becoming fuller, specifically the entry of the Moog synthesizer alongside heavier rhythmic playing.

### 2. Structural Clarity: Chroma vs. Timbre SSMs

Comparing the two Self-Similarity Matrices (SSMs) reveals the A-B-A macro-structure of the song, but they show distinctly different levels of clarity regarding the micro-structure:

* **Chroma-based SSM (Harmonic Structure):** The structure here is exceptionally clear. Crucially, the dark off-diagonal blocks (comparing the first verse to the final verse) display an intricate "checkerboard" pattern. This perfectly visualises the cyclical chord progression repeating measure-by-measure within the verses. 
* **Timbre-based SSM (Textural Structure):** While the overarching Verse-Chorus-Verse structure is still visible, this matrix is significantly noisier and less sharply defined. This illustrates the reality of the acoustic recording: while the underlying chords repeat almost exactly (captured by chroma), the physical performance, drum dynamics, and vocal nuances (captured by timbre) are uniquely varied throughout every repetition.
