# User Documentation

## Importing Data

### Importing Meter Data
SEED 2.6.0 incorporates the ability to import interval meter data. The document linked below explains how to import meter data from ENERGY STAR Portfolio Manager and Green Button files

- [Meter Data (PDF)](resources/SEED Platform V2_6_ Meter Data.pdf)

## Field Mappings

List of SEED field names for Mapping data

- [Field Mappings (PDF)](resources/MappingFieldstotheSEEDdatabase.pdf)

## Data Cleansing Rules
List of currently implemented data cleansing rules

- [Cleansing Rules (PDF)](resources/DataCleansing.pdf)

## Filtering

- [SEED Filtering in Lists (PDF)](resources/SEED Filtering.pdf)

- [Data Quality Checks with Filters-Labels (Video)](resources/Data Quality Checking with Filters-Labels.swf)

## GIS Features
SEED v2.5.0 and above incorporates some GIS functionality

- [GIS Features (PDF)](resources/SEED Platform V2_5_ GIS Features.pdf)

## Excel&trade; Files

### Multi-Tab Files

Multi-tab Microsoft Excel&trade; files are only partially supported by SEED. It can read a Microsoft Excel&trade; file that has multiple tabs, but it will only read the first tab, so make sure that the data you want the program to import is in the first tab. If the mapping screen only has one field in it, this might be the problem. 

### Date Fields in Excel&trade; Files
If you are importing an Excel&trade; file (XLS, XLXS) into SEED, make sure that any field defined with a "date" format in Excel&trade; actually has data in it that is a date. If a field has non-date data (such as an integer) in a date-formatted field, SEED will not import that record.  