# VAE
Variational Autoencoder

Download images from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
Extract to folder 'img_align_celeba'.

In vae_celeba.py:

- Set URI for images folder (this path is outside of the Git folder (too large)):
<br><code>img_uri = '../img_align_celeba/' + img_id</code>

- Change the name for the 'image_name' bellow if needed. It is the label for the first column in the 'list_attr_celeba.csv'.
<br><code>img_id = df.loc[idx].image_name</code>
        
