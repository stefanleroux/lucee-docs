
```lucee
<!--- cfloop: array --->
<!--- create an array of pets --->
<cfset pets = ["Dog","Cat","Mouse","Snake","Possum"]>

<!--- loop over array and print out pets --->
<cfoutput>
<cfloop index="p" array="#pets#">
	#p# <br />
</cfloop>
</cfoutput>
```
