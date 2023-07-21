[] Implement Search (Feed Component)
notes. useStates for ... searchText, searchTimeout, searchedResults
filterPrompts = (searchtext) => {
const regex = new RegExp(searctext, "i")
return allPosts.filter(
(item) =>
regex.test(item.creator.username)
regex.test(item.tag)
regex.test(item.prompt)
)
}

handleSearchChange

- Search by prompt
- Search by tag
- Search by username

[] Implement Click on tag (Feed Component)

[] Implement view other profiles
