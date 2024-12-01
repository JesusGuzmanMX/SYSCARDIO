# Heuristic correction

Sometimes the UNET predicts more than four heart chambers mask for counted frames in sequence and also some frames in the sequence shows overlapping heart chambers that did not match the actual anatomy of human heart. The heuristic-based corrective method automatically detects this overlap issues considering the Euclidean distance parameter as threshold to make the right cut over the mask.
