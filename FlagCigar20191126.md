一：BAM FLAG
(1)	143:1+2+4+8+128:This read is one of paired reads, Each one correctly aligns to the reference sequence, The read does not align to the reference sequence, The mate-pair read paired with the read does not match the reference sequence, In paired reads, this read is the second alignment with the reference sequence.
(2)	99:1+2+32+64:This read is one of paired reads, Each one correctly aligns to the reference sequence, The reverse complementary sequence of the mate-pair read paired with the read can be aligned to the reference sequence, In paired reads, the read is the first paired with a reference sequence.
(3)	516：4+512：The read does not align to the reference sequence，The read does not pass quality control.
(4)	2064:16+2048: The read has a reverse complementary sequence that aligns to the reference sequence, Supplementary matched read.
(5)	147:1+2+16+128: This read is one of paired reads, Each one correctly aligns to the reference sequence, The read has a reverse complementary sequence that aligns to the reference sequence, In paired reads, this read is the second alignment with the reference sequence.
二：BAM CIGAR
(6)	14M2D31M：The first 14bp can match on the reference sequence，Compared to the reference genome there are 2bp deletions, Finally, 31bp is matched to the reference genome.
(7)	3S6M1D5M: Three genomes that cannot be aligned at the front of the sequence, but still exist in Seq, The 6bp can match on the reference sequence，Compared to the reference genome there are 1bp deletion, Finally, 5bp is matched to the reference genome.
(8)	6M14N5M: The first 6bp can match on the reference sequence，The reference 14 sequence is skipped, Finally, 5bp is matched to the reference genome.
(9)	7M5D8M2I14M : The first 7bp can match on the reference sequence，Compared to the reference genome there are 5bp deletions, Then, 8bp is matched to the reference genome, Compared to the reference genome there are 2bp insertions, Finally, 14bp is matched to the reference genome.
(10)	how long is the read with alignment CIGAR of 7M5D8M2I14M?
   The length of the 31bp.


