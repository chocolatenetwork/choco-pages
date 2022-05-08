
### Teams section
```html
  <!-- <div class="team">
    <h2 id="team">Team</h2> -->
    <!-- https://jekyllrb.com/docs/datafiles/ -->
    <!-- <section class="team_cards"> -->
      <!-- 
                            1. Store member props as a json blob on this repo and load into app. If too slow, load another way.
                            2. Figure out how to style the cards nicely and use one method
                            3. Map each of them into responsive cards and display under this section. This would be a grid ideally well-placed and responsive
                            interface MemberProps {
                              name: string;
                              image: string;
                              socials: any;
                            }
                            /**
                             *
                             * @description Renders a memberview
                             */
                            const Member: React.FC<MemberProps> = function (props) {
                              const { image, name } = props;
                              return (
                                <article>
                                  <figure>
                                    <img src={image} alt='' />
                                    <figcaption>{name}</figcaption>
                                  </figure>
                                  {/* title here */}
                                  <span>{/* Render Socials */}</span>
                                </article>
                              );
                            };
                            
                            const TeamList: React.FC = function () {
                              const [team] = useState<any[]>([]);
                              // fetch team from git - do this lazily on app instantiation.
                              // teamlist.mapeach to img,name,title
                              //  fill in members from fetch team
                              const renderTeam = team.map((member) => <Member {...member} />);
                              return <section>{renderTeam}</section>;
                            };
                            
                            /**
                             * @description  The team page
                             *
                             */
                            const Team: React.FC = function () {
                              return (
                                <article>
                                  <h1>Meet our Team</h1>
                                  <TeamList />
                                  <p>
                                    <b className='highlight-team'>I</b>ntegrity <b className='highlight-team'>D</b>iscipline{' '}
                                    <b className='highlight-team'>E</b>fficiency <b className='highlight-team'>A</b>daptability
                                  </p>
                                  <p>
                                    Team <img src={ChocolateRedSmall} alt='chocolate-emoji' /> is a meritocracy. No space for
                                    big egos here, only big dreams.
                                  </p>
                                </article>
                              );
                            };
                            
                            export default Team;
                            
                             -->
  
    <!-- </section> -->
    <!-- </div> -->


```
### Next up..
Now I'm finally ready to add content. Qn: Should I deploy beta two before then?? Weekend isn't over but still, might not get chance.

### Just me..
Idea: Use type scale for space ranks. As I just noticed that 1rem-3rem has actually been polkadot.network using type scale 0.8rem - 3ranks or more. Moreso since they use same scale as us.