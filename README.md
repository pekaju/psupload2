# psupload2

Replaces New-TemporaryFile with [System.IO.Path]::Combine([System.Environment]::GetFolderPath('Desktop'), [System.IO.Path]::GetRandomFileName())
