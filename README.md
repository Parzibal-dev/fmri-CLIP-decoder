# fMRI-CLIP decoder

**TODO list:**
- [ ] Also pre-embed and save the sentences data, and see how they fair up in the same modality evaluation.
- [ ] Figure out a way to conver Tukute fMRI data to a similar version to Pereira's, and check them as well in the same modality evaluation
- [ ] Evaluate visual data as well, based on only textual training.
- [ ] Try to add tukute + sentences to textual training as well, and see if it changes things?
- [ ] Add other people's data to the fmri (and to the drive as well)
- [ ] SGD/Adam on the amount of voxels for the best results (same modality? cross modality)
- [ ] Train on text + visual data (figure out best configuration - maybe add sentences/tukute, always eval with cross validation)
- [ ] Finish explaining all of the steps we currently have as base.