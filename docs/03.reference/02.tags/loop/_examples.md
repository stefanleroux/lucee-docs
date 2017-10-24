```luceescript
<cfquery datasource="UserDB" name='qUser'>
	Select Username, FirstName, LastName
	From UserDB.User
</cfquery>

<cfloop query='qUser'>
	<cfoutput>
		#Username# - #FirstName# - #LastName# <br/>
	</cfoutput>
</cfloop>


<cfset userArray = ["John Spartan", "Simon Phoenix", "Lenina Huxley", "Alfredo Garcia", "Edgar Friendly"]>

<cfoutput>
<cfloop index="a" array="#userArray#">
	#a# <br />
</cfloop>
</cfoutput>

```
