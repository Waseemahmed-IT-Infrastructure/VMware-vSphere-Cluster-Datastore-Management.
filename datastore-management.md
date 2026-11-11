
# VMware Datastore Management

## Overview

This document covers basic datastore management in VMware vSphere, including storage checks and ISO uploads.

## Checking Datastore Capacity

1. Log in to vCenter.
2. Open the Storage section.
3. Select the required datastore.
4. Check total capacity, used space and free space.
5. Review any datastore warnings or alerts.

## Uploading an ISO File

1. Open the required datastore in vCenter.
2. Select Files or Datastore Browser.
3. Create a folder for ISO files if needed.
4. Click Upload Files.
5. Select the ISO file from your computer.
6. Wait for the upload to finish.
7. Verify that the ISO is available in the datastore.

## Using an ISO for a VM

1. Open the virtual machine.
2. Select Edit Settings.
3. Find the CD/DVD drive.
4. Choose Datastore ISO File.
5. Select the required ISO.
6. Enable Connect at power on if needed.
7. Save the settings.

## Basic Storage Checks

- Check free datastore space before creating a VM.
- Verify the correct datastore is selected.
- Review storage alerts.
- Check whether the datastore is accessible to the required host.
- Avoid deleting VM files without confirming their purpose.

## Common Issues

| Issue | What to Check |
|---|---|
| ISO not visible | Correct datastore and folder |
| Upload fails | Permissions, connection and free space |
| Datastore almost full | Storage usage and available capacity |
| VM cannot access storage | Datastore accessibility and host status |

## Note

These are general VMware vSphere steps. Menu names may vary depending on the vCenter version.
