## AI Deadlines 
Countdown timers to keep track of a BK conference deadlines. For DBDC laboratory (dbdc.ajou.ac.kr)
## Contributing
Contributions are very welcome!
In case of you want to update the sub(subjects), please let me know. 
To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` for BK scores
- Optionally add `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Optionally add `hindex` (refers to h5-index from [here](https://scholar.google.com/citations?view_op=top_venues&vq=eng))
- Example:
    ```yaml
    - title: BestConf
      year: 2022
      id: bestconf22  # title as lower case + last two digits of year
      full_name: Best Conference for Anything  # full conference name
      link: link-to-website.com
      deadline: YYYY-MM-DD HH:SS
      abstract_deadline: YYYY-MM-DD HH:SS
      timezone: Asia/Seoul
      place: Incheon, South Korea
      date: September, 18-22, 2022
      start: YYYY-MM-DD
      end: YYYY-MM-DD
      paperslink: link-to-full-paper-list.com
      pwclink: link-to-papers-with-code.com
      hindex: 100.0
      sub: SP
      note: Important
    ```
- Send a pull request
  
## for DBDC members
Raw Data Link:https://dbdc.quickconnect.to/oo/r/102c4yNlggVpWEYEqCdlXQdo2WFeBa8T 

If you want to contribute through the table, you must fill in all the orange cells. Also, you should write according to the format by looking at the adjacent cells (or the template in this readme).
The link to the table is as follows, and id/pw login is required.
Updates for 2025 conferences are needed. We kindly ask for your participation..!

## License

This project is licensed under [MIT][1].

It uses:

- [IcoMoon Icons](https://icomoon.io/#icons-icomoon): [GPL](http://www.gnu.org/licenses/gpl.html) / [CC BY4.0](http://creativecommons.org/licenses/by/4.0/)

