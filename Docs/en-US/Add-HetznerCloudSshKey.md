---
external help file: HetznerCloud-help.xml
Module Name: HetznerCloud
online version:
schema: 2.0.0
---
# Add-HetznerCloudSshKey

## SYNOPSIS

Adds an SSH public key

## SYNTAX

```powershell
Add-HetznerCloudSshKey [-Name] <String> [-PublicKey] <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION

This cmdlet adds the public key of an existing SSH key pair to use in the Hetzner Cloud.

## EXAMPLES

### Example 1

```powershell
PS C:\> Add-HetznerCloudSshKey -Name 'mykey' -PublicKey 'ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDLF1P9cSi8YXclN1vpLOFKydIczWbfJj92RWLOeo3dmrPGkeBtmtpJU3DWqWxJkelagr5oQGn5XRu08GfdKJyPCZEoThzqaRHOKZGN79JpRjabIm8boHQE04cYP+0L4wbN53dpthPCeA6FkDNyKoJ+K8qTqmLDGsO2ztVLBMXEU3kiler/4jSLP+kbMn5tSuHlyZdsv+4DaZb3atwkC7yrZd/uF4t8uC+xB6k3USHqmcgguzCu25V0yGqjlvDb2Jz1InoYdpCqbEMIvHVxMsd7dJHYO6afgn8GWOHsbpyPzJn2v73nldtJUJoSr2UDrpwkKZ3zVUnO/9aw5Y5qiR7 someone@somewhere'
```

Adds a new SSH public key called `mykey`.

## PARAMETERS

### -Name

Name of the SSH public key

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PublicKey

SSH public key to be added

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).
