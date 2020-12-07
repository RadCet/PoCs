# research
# 
### Description
> IrfanView 4.53 allows a User Mode Read AV starting at MNG.DLL + 0x15C85
>
> ------------------------------------------
>
> [VulnerabilityType Other]
> User mode read access violations
>
> ------------------------------------------
>
> [Vendor of Product]
> Irfanview
>
> ------------------------------------------
>
> [Affected Product Code Base]
> Irfanview - 4.56
>
> ------------------------------------------
>
> [Affected Component]
> Plugin MNG.dll read file mng.
> MNG.DLL + 0x15C85
> 10015c85 	8b8b94040000	mov ecx,dword ptr [ebx+494h]
>
> ------------------------------------------
>
> [Attack Type]
> Local
>
> ------------------------------------------
>
> [Attack Vectors]
> to exploit vulnerability, someone must open a crafted MNG file.
>
> ------------------------------------------
>
> [Discoverer]
> ThanhTP, radcet of VinCSS (a member of Vingroup)
>
> ------------------------------------------
>
> [Reference]
> https://www.irfanview.com/main_history.htm
