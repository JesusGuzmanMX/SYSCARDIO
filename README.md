# SYSCARDIO

This is the SYSCARDIO system, used in the article [Robust cardiac segmentation corrected with heuristics](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0293560) and features three blocks:

* Cone segmentation: a segmentation algorithm capable of accurately detecting cone shapes (as it has been trained and refined with multiple data sources).
* U-Net for cardiac chambers segmentation in 4-CH images: a robust cardiac segmentation algorithm based on the popular U-NET architecture capable of accurately segmenting the four cavities with a reduced training dataset.
* Heuristic correction for correct chambers overlapping: a post-processing step which refines the shape and contours of the segmentation based on heuristics provided by the clinicians.

All three blocks works in a secuencial way (as it shown in the follow figure).

![SYSCARDIO Workflow](Workflow.png)

## Citation

```yaml
@article{Cervantes_McPherson2023,
  title={Robust cardiac segmentation corrected with heuristics}, volume={18}, DOI={10.1371/journal.pone.0293560},
  number={10}, journal={PLOS ONE}, author={Cervantes-Guzmán, Alan and McPherson, Kyle and Olveres,
  Jimena and Moreno-García, Carlos Francisco and Robles, Fabián Torres and Elyan, Eyad and Escalante-Ramírez, Boris},
  year={2023}, month={Oct}
} 
```



Alan Cervantes Guzman  
[LAPI, UNAM](https://lapi.fi-p.unam.mx/)
