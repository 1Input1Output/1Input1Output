import GoogleLogo from './GoogleLogo';
import SearchBox from './SearchBox';
import SignInButton from './SignInButton';
import NavBar from './NavBar';
import SearchResults from './SearchResults';
import Sidebar from './Sidebar';

import App() {
    return(
<div>

<div>
<GoogleLogo/>
<SearchBox/>
<SignInButton/>
</div>
<SearchResults/>
<Sidebar/>
</div>

    );
}
export default App;
