# <img  src="https://i.ibb.co/cDxhM27/Gruppe-2.png"  alt="logo"  height="30"  />&nbsp;&nbsp;AMEML&nbsp;&nbsp;-&nbsp;&nbsp;Amazon Music Export My Library

> A tool to export your Amazon Music Songs from "My Library"<br />
> Works without active Amazon Music subscription<br />
> FreeYourMusic friendly
<br />

## Requirements
You need to have Amazon Music installed
<br />
You can get the installer [here](www.amazon.de/Amazon-Music-für-PC-Download/dp/B00CTTEKJW)
<br />
<br />

## Instalation

Head to the [latest release](https://github.com/deadlinecode/AMEML/releases/latest), grab the file for your PC and download it
<br />
<br />

## Usage

Just start the programm by double clicking the downloaded file
<br />
A console window will pop up telling you what you need to do
<br />
<br />

`If a window pops up telling you to install a certificate or let a programm through the firewall click accept`<br />
`The programm will use the certificate only to decrypt the https traffic of the `
<br />
<br />

After the programm has gathered all necessary informations you can choose between 3 formats
| Format | Explanation |
| ------ | ----------- |
| CSV    | All data in CSV Format with headers |
| JSON   | All data in JSON (array containing objects) |
| CSV (FreeYourMusic friendly)&nbsp;&nbsp;&nbsp;&nbsp; | CSV with less data and formated so FreeYourMusic recognizes it&nbsp;&nbsp;&nbsp;&nbsp;<br />(`name`, `artist`, `album`) |
> [Scroll down](#data-infos) to see all informations you get
<br />

After the programm is done the file will be saved in the current folder where the programm is located
The file name will be the current date and time in the following format `11-07-2023T22-25.csv`
<br />
<br />

## Data infos
You will get following data:
- objectId
- fileName
- fileExtension
- fileSize
- creationDate
- lastUpdatedDate
- orderId
- asin
- purchaseDate
- localFilePath
- md5
- status
- purchased
- uploaded
- title
- sortTitle
- rating
- marketplace
- physicalOrderId
- assetType
- artistName
- artistAsin
- contributors
- trackNum
- discNum
- primaryGenre
- duration
- bitrate
- composer
- songWriter
- performer
- lyricist
- publisher
- errorCode
- instantImport
- primeStatus
- isMusicSubscription
- albumName
- albumAsin
- albumArtistName
- albumArtistAsin
- albumContributors
- albumRating
- albumPrimaryGenre
- albumReleaseDate
- sortArtistName
- sortAlbumName
- sortAlbumArtistName
- audioUpgradeDate
- parentalControls
- assetEligibility
- eligibility
- internalTags



### Disclaimer
AMEML and the creator deadlinecode are not affiliated with Amazon Music and assumes no legal responsibility for the use of this programm.
