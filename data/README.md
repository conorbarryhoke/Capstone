# Data guide
This is the repository for all data used in the various workbooks.

## Guide
The data is generated from workbooks as follows:

<span><img src="https://raw.githubusercontent.com/conorbarryhoke/Capstone/master/assets/data_files_description_sources.bmp"><span>

## Feature dictionary
A number of features were created through meta-analysis and added back to the information obtained from YouTube.

A dictionary is provided here:

<table class="table table-bordered table-hover table-condensed">
<thead><tr><th title="Field #1">id</th>
<th title="Field #2">feature_name</th>
<th title="Field #3">description</th>
</tr></thead>
<tbody><tr>
<td align="right">1</td>
<td>view_class</td>
<td>integer values (rounded) of nearest order of magnitude</td>
</tr>
<tr>
<td align="right">2</td>
<td>caption</td>
<td>whether or not the video has a caption</td>
</tr>
<tr>
<td align="right">3</td>
<td>definition</td>
<td>high def or standard def</td>
</tr>
<tr>
<td align="right">4</td>
<td>duration</td>
<td>length of video in seconds</td>
</tr>
<tr>
<td align="right">5</td>
<td>licensedContent</td>
<td>whether or not video contains licensed music</td>
</tr>
<tr>
<td align="right">6</td>
<td>regionRestriction</td>
<td>whether or not video is restricted in some regions</td>
</tr>
<tr>
<td align="right">7</td>
<td>contentRating</td>
<td>whehter or not video has a content rating (e.g. explicit lyrics)</td>
</tr>
<tr>
<td align="right">8</td>
<td>year</td>
<td>two digit year of upload</td>
</tr>
<tr>
<td align="right">9</td>
<td>month</td>
<td>month of upload</td>
</tr>
<tr>
<td align="right">10</td>
<td>month_day</td>
<td>day of month (1-31) of upload</td>
</tr>
<tr>
<td align="right">11</td>
<td>year_day</td>
<td>day of year (1-365) of upload</td>
</tr>
<tr>
<td align="right">12</td>
<td>week_day</td>
<td>week day (0-6) of upload</td>
</tr>
<tr>
<td align="right">13</td>
<td>week</td>
<td>week number of upload (0-52)</td>
</tr>
<tr>
<td align="right">14</td>
<td>description_sentiment</td>
<td>total sentiment of words in description</td>
</tr>
<tr>
<td align="right">15</td>
<td>description_wordcount</td>
<td>total space-separated words in description</td>
</tr>
<tr>
<td align="right">16</td>
<td>tags_sentiment</td>
<td>total sentiment of words in tag</td>
</tr>
<tr>
<td align="right">17</td>
<td>tags_wordcount</td>
<td>total number of tags on video (comma separated)</td>
</tr>
<tr>
<td align="right">18</td>
<td>title_sentiment</td>
<td>total sentiment of words in title</td>
</tr>
<tr>
<td align="right">19</td>
<td>title_wordcount</td>
<td>number of words in title (space separated)</td>
</tr>
<tr>
<td align="right">20</td>
<td>title_featuring</td>
<td>whether or not the title contains featuring artsist (ft, feat, featuring etc)</td>
</tr>
<tr>
<td align="right">21</td>
<td>intitle_a</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">22</td>
<td>intitle_b</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">23</td>
<td>intitle_c</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">24</td>
<td>intitle_d</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">25</td>
<td>intitle_e</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">26</td>
<td>intitle_f</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">27</td>
<td>intitle_g</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">28</td>
<td>intitle_h</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">29</td>
<td>intitle_i</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">30</td>
<td>intitle_j</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">31</td>
<td>intitle_k</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">32</td>
<td>intitle_l</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">33</td>
<td>intitle_m</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">34</td>
<td>intitle_n</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">35</td>
<td>intitle_o</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">36</td>
<td>intitle_p</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">37</td>
<td>intitle_q</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">38</td>
<td>intitle_r</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">39</td>
<td>intitle_s</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">40</td>
<td>intitle_t</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">41</td>
<td>intitle_u</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">42</td>
<td>intitle_v</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">43</td>
<td>intitle_w</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">44</td>
<td>intitle_x</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">45</td>
<td>intitle_y</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">46</td>
<td>intitle_z</td>
<td>number of occurences of letter in the title</td>
</tr>
<tr>
<td align="right">47</td>
<td>title_length</td>
<td>total character length of title</td>
</tr>
<tr>
<td align="right">48</td>
<td>lv_ratio</td>
<td>ratio of likes to views (log on log)</td>
</tr>
<tr>
<td align="right">49</td>
<td>comment_view_ratio</td>
<td>ratio of comments to views (log on log)</td>
</tr>
<tr>
<td align="right">50</td>
<td>like_dislike_ratio</td>
<td>ratio of likes to dislikes (log on log)</td>
</tr>
<tr>
<td align="right">51</td>
<td>is_weekend</td>
<td>whether video was published on the weekend</td>
</tr>
<tr>
<td align="right">52</td>
<td>is_friday</td>
<td>whether video was published on a Friday</td>
</tr>
</tbody></table>
