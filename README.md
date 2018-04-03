# Manual Page Skeleton  :skull:
![](https://i.imgur.com/TBEB1rS.png)


## Usage

1. Download [skeleton.x](https://github.com/AlexanderBodin/man-page-skeleton/blob/master/skeleton.x)

2. Open **skeleton.x** with your favourite text-editor and replace the content in lines: 1, 4, 5, 7, 8, 11, 13, 14, 16, 18, 20.

3. Save the file and give it a new name. (*Example: human.1*)
![](https://i.imgur.com/0wh26Bs.png)

4. Compress the man page (*See Example*)

![](https://i.imgur.com/mPqoS2u.png)

5. Evaluate where to move the compressed man page
![](https://i.imgur.com/fLcB8cn.gif)
        <details>
           <summary>Subdirectories for the different man page sections (Click to expand)
          </summary>
         <p>![](https://i.imgur.com/XMOHVYP.png)</p>
         </details>

6. Copy the compressed man page into the man page directory of your choice (*See Example*)
```
cp human.1.gz /usr/share/man/man1
```
7. Make sure that the man page can be called by man. (*See Example*)
![](https://i.imgur.com/HHvY18g.gif)


## Development

To improve or suggest something simply open an issue or submit a Pull.

## Contributing

1. Fork it (https://github.com/AlexanderBodin/man-page-skeleton/fork)
2. Create your feature branch (*git checkout -b my-new-feature*)
3. Commit your changes (*git commit -am 'Add some feature'*)
4. Push to the branch (*git push origin my-new-feature*)
5. Create a new Pull Request

## License
[MIT 2018 Alexander Bodin](https://github.com/AlexanderBodin/man-page-skeleton/blob/master/LICENSE)
