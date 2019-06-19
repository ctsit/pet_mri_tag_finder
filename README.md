Running this program is very simple.
`python pet_mri_fill_in.py <path_to_folder>`

The program will create two csv files-- one for PET images and one for MRI images. The folder can contain both mixed together and they will be seperated via the Modality tag.

While there is a flag for building off previously created csvs, it is untested and should not be used. If you need to run the program twice, rename the files made in the first run or run the program on a different day for the second run.