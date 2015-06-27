The WaveHC Library was developed for the Adafruit Arduino Wave Shield.   It supports both standard SD and high capacity SDHC flash cards.  The cards may be formatted with either FAT16 or FAT32 file systems.

The WaveHC Library is based on the four C++ classes, SdReader, FatVolume, FatReader and WaveHC.

SdReader is a standalone class that provides raw read access to standard SD cards and high capacity SDHC cards.

The FatVolume class provides access to data structures on FAT16 and FAT32 volumes.

File read access to FAT16 and FAT32 volumes is provided by the FatReader class.

The fourth class, WaveHC, is a modified version of Ladyada’s AF\_Wave class that uses FatReader to read and play WAV files.

See the readme.txt file and library documentation for more information