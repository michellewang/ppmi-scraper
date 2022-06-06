A downloader of PPMI metadata and imaging data files.

# Example usage

```
import ppmi_downloader
ppmi = ppmi_downloader.PPMIDownloader(<ppmi_login>, <ppmi_password>)

# Download metadata files
ppmi.download_metadata(['Demographics.csv', 'Age_at_visit.csv'])

# Download 3D imaging metadata
ppmi.download_3D_mri_info()

# Download imaging data
ppmi.download_imaging_data([3001, 3003, 3011])
```